# Snake Model Test
It seems like one repository for each model seem like a better idea. A few pointers before you start making a repository for your own project.
1. A model repository should contain the UCI file and associated WDM files.
2. WDM files can be large and GitHub doesn't like files >100 MB. Use 7z and zip files to 7z format using maximum compression. This will significantly bring down the size of the file.
3. Make sure that git ignores the wdm files when syncing.
4. Additionally, make sure that git ignores all the binary files, echo files, out files, and pltgen files. These files are produced every run and there is no point syncing them.
5. Additional files that should accompany a release are EXS file(s), graph specification files, and a report that may be in PDF or word format. PDF files of maps, and/or GIS files of map will be super useful.
5. When you are at a stage that you think that your model is final. Create a release with a version number and add as many details as you can. The release will contain all the files upto that point.
6. When and if you modify the model due to any reason, create a new release.
