# ms-paint web

the binary for mspaint.exe running in your browser via the CheerpX 86x wasm emulator

Since i have moved away from windows, there have been a couple things I have begun to miss, but probably the most prominent of the group is mspaint. I need a simple program for drawing diagrams or making little doodles from time to time as a student, and mspaint was the one I grew up with. There is a certain charm that mspaint has, which the other alternatives lack. And so I cast myself into windows driver hell, for no good reason other than to run mspaint, of my own free will.

So because of how cheerpx works, and because mspaint doesn't play well with wine, the plan is to actually have the linux vm run by cheerpx run a windows vm, which will then be able to run mspaint. I am not sure how performant this will be, but from what i can tell cheerpx is actually quite performant

## Roadmap

- [x] Obtain the 32 bit binary for ms paint
- [x] create small windows 10 vm
- [ ] get that running from inside a docker container
- [ ] copy docker filesystem into a disk image
- [ ] run disc image inside cheeprX
- [ ] save images from ms paint to user's machine

## Resources

- <https://cheerpx.io/docs/guides/custom-images>
- <https://gitlab.winehq.org/wine/wine/-/wikis/Wine-User%27s-Guide>
- <https://github.com/scottyhardy/docker-wine>
- <https://webvm.io/alpine.html>
