**This is an empty dummy repo\*, links to the individual repos for each picture set are below.**

## [Photogrammetry Test Sets Group (CC-BY)](https://gitlab.com/photogrammetry-test-sets)

### License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

### Attribution

To make attribution easy, all the repos have an attribution template filled out with/without links ready to copy.

### My Test Sets

#### Sets Used in this Video: [How to Scan Objects into 3D Models II - Settings and Setup Comparisons](https://youtu.be/7pGJ8rWiecw)

- [Dice - Turntable - Strong Lights - Heavily Textured w Watercolors](https://gitlab.com/photogrammetry-test-sets/dice-turntable-strong-lights-heavily-textured-w-watercolors)
- [Dice - Turntable - Strong Lights - Opaque Watercolors](https://gitlab.com/photogrammetry-test-sets/dice-turntable-strong-lights-opaque-watercolors)
- [Dice - Turntable - Strong Lights - Opaque Watercolors + Lightly Textured](https://gitlab.com/photogrammetry-test-sets/dice-turntable-strong-lights-opaque-watercolors-lightly-textured)
- [Dice - Turntable - Strong Lights - Thin Messy Watercolors](https://gitlab.com/photogrammetry-test-sets/dice-turntable-strong-lights-thin-messy-watercolors)
- [Skull - Cameramoves - Flash - No Background](https://gitlab.com/photogrammetry-test-sets/skull-cameramoves-flash-no-background)
- [Skull - Cameramoves - Weak Light - No Background](https://gitlab.com/photogrammetry-test-sets/skull-cameramoves-weak-light-no-background)
- [Skull - Turntable - Strong Lights - No Background - Dotted](https://gitlab.com/photogrammetry-test-sets/skull-turntable-strong-lights-no-background-dotted)
- [Skull - Turntable - Strong Lights - No Background - Dotted - Shallow DOF](https://gitlab.com/photogrammetry-test-sets/skull-turntable-strong-lights-no-background-dotted-shallow-dof)
- [Skull - Turntable - Strong Lights - White Background](https://gitlab.com/photogrammetry-test-sets/skull-turntable-strong-lights-white-background)
- [Skull - Turntable - Strong Lights - White Background - Dotted](https://gitlab.com/photogrammetry-test-sets/skull-turntable-strong-lights-white-background-dotted)
- [Skull - Turntable - Strong Lights - White Background - Ink Splashed Textureless Areas](https://gitlab.com/photogrammetry-test-sets/skull-turntable-strong-lights-white-background-ink-splashed-textureless-areas)
- [Skull - Turntable - Strong Lights - White Background - Matte Powder](https://gitlab.com/photogrammetry-test-sets/skull-turntable-strong-lights-white-background-matte-powder)


### Other's Test Sets

See below for how you can contribute.

<!-- Please check each repo for how the owners prefer to be credited. -->

---

## Other External Test Sets (under varying licenses)

Please file an issue if there are any dead links or you would like a link added.

### Downloading
For those that are hosted in github repos, for downloading a specific folder you can either use [DownGit](https://minhaskamal.github.io/DownGit/#/home) or there's a chrome extension called [GitZip](https://chrome.google.com/webstore/detail/gitzip-for-github/ffabmkklhbepgcgfonabamgnfafbdlkn) but you will need a Github account you will need to know how to get a github token. It should also be possible to do a [shallow clone with a sparse checkout]((https://stackoverflow.com/questions/600079/how-do-i-clone-a-subdirectory-only-of-a-git-repository/13738951#13738951), but I've never tried it, since the above is 100x easier.

### Links

- [bundler_sfm examples (Kermit + ET)](https://github.com/snavely/bundler_sfm/tree/master/examples) - Small images sets, but not very high quality as the images are quite small, but they're what many photogrammetry programs are tested with since they can be processed very quickly. There's also an [online 3D demo of the Kermit set reconstructed with Regard3D here](http://www.regard3d.org/r3d_demos/demo_kermit_texture.html).

- [openMVG/ImageDataset_SceauxCastle](https://github.com/openMVG/ImageDataset_SceauxCastle) - A small set (~10 images), decent image size. There's also an [online 3D demo of it reconstructed with Regard3D here](http://www.regard3d.org/r3d_demos/demo_sceaux.html).

- [rperrot/ReconstructionDataSet](https://github.com/rperrot/ReconstructionDataSet/) - Contains 9 picture sets (including a statue, churches and related architectural details) with large high quality images (slightly large than mine). Licensed under CC-BY-NC 3.0.

- [DTU Robot Image Data Sets](http://roboimagedata.compute.dtu.dk/?page_id=24) - Mind boggling huge amount of super high quality picture sets (multiple light directions captured per position). Only problem is the half-size downloads for the 2010 set aren't available and the full size downloads are HUGE (39GB+ each). Also there's no list of which sets contain which items. The smallest download available (a sample of the 2014 set) is ~7GB but it also comes with a lot of extra stuff and only two picture sets.

---

## *Why This is an Empty Repo

Initially I was just going to make one giant gitlab repo (since it's above github's 1GB limit), but it's not possible to download single folders from gitlab as far as I know. I considered making a github organization with all the folders as repos but github doesn't really make it easy to group repos the way gitlab does.

So instead all the photo sets are different repos under one gitlab group. Since repos can also be part of multiple groups, this means, should someone want to contribute any picture sets, their repo/project can just be added to the group.

## Contributing

Because of the above, to contribute photos you must use a gitlab repo. I will add any repos to the group that contain images licensed under a CC-BY license*.

For other licenses, or if you don't want to host them on github, etc, I can add a link to the "Other External Test Sets " section, just open an issue or send me an email.

I would prefer full sets that allow for the reconstruction of the entire object, but I will accept partial sets as well.

Repos should be structured similar to mine:

- Only one set per repo to make them easy for people to download.
- Number the Images with enough Leading Zeros (do not duplicate numbers throughout the repo, e.g. in the case of folders).
- Use folders if you changed the lighting/camera settings slightly for some section (e.g. like for photographing the bottom of something).
- Include the plain text CC License File in the repo.
- "Embed" the license in the README (like I did above).
- Link to this repo or the gitlab group.
- Specify a preferred attribution template.


\*Please be sure you are free to license them this way, I'm not responsible for any test sets that are not mine. For example, I think it's a bit of a gray area publishing a picture set of something like a toy or a modern sculpture that is still under copyright, especially given *they can/will be used to reconstruct the object*.

### Sharing a Project

**Please file an issue [HERE on github](https://github.com/AlansCodeLog/photogrammetry-test-sets/issues) before sharing a project/repo.**

You will need to request access to the group on gitlab.

Then this is [how groups are shared](https://docs.gitlab.com/ee/user/project/members/share_project_with_groups.html), though the labels are now "Invite Group".

