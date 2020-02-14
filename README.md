# SI for "A Computational Study of Structural and Excitonic Properties of Chlorosomes"

## files in chapter * are stored in chapter_* folders

## note for CTubeGen software in chapter_5 folder
- A software I developed for generating arbitray chlorosomal tubes, CTubeGen_Feb2020.app.

- It is a dustributed package for macOS, with a graphic user interace. 

- The usage is straighforward: 

0. download the CTubeGen_Feb2020.dmg uncompress the CTubeGen_Feb2020.app file & open the app file (right-click --> open).
1. in the UI, fill in the n1 and n2 integars (chiral indices).
2. click "convert ==>" button; below you will see the estmiated chiral angle and radius; try different n1 and n2 until satisfied.
3. fill in the length
4. click "select path" button; save a desired output file name xxx.gro
5. click "RUN" button; wait until the LOG window in the right indicating that the packing is done.
6. use VMD to view the output gro file. "name MG" and "index % 121 < 27" selection rule in VMD will show only the Mg atoms and head parts, respectively.



