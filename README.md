# ms-paint web

the binary for mspaint.exe running in your browser via the CheerpX wasm emulator

Since i have moved away from windows, there have been a couple things I have begun to miss, but probably the most prominent of the group is mspaint. I need a simple program for drawing diagrams or making little doodles from time to time as a student, and mspaint was the one I grew up with. There is a certain charm that mspaint has, which the other alternatives lack. And so I cast myself into windows driver hell, for no good reason other than to run mspaint, of my own free will.

## Roadmap

- [ ] Obtain the x32 binary for ms paint from an emulated vm
- [ ] get the ms paint gui working from inside a docker (from inside a windows vm)
  - <https://cheerpx.io/docs/guides/custom-images>
- [ ] dump docker container into a disc image
- [ ] run disc image inside cheeprX
- [ ] save images from ms paint to user's machine
