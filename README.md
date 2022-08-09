# add-pdf-metadata

Add metadata to a pdf using pdflatex regardless of how the original pdf was produced. Here are the steps:
1. Make sure you have an up to date LaTeX system installed such as [TeX Live](https://www.tug.org/texlive/).
2. Read the comments in the file [AddMetadataToPdf.tex](AddMetadataToPdf.tex).
3. Edit the line in that file where indicated with the name of the source pdf that you want to add metadata to.
4. Run `pdflatex AddMetadataToPdf.tex` at the command line, which will produce a file named `AddMetadataToPdf.pdf` 
  with the contents of the original pdf file, but with the addition of your specified metadata.
5. Change the name of the original pdf if you want to keep it as a backup, or delete the original if you don't.
6. Rename `AddMetadataToPdf.pdf` to the name of the original pdf file.
7. Alternatively, you could rename the original pdf before the above procedure, and then rename `AddMetadataToPdf.tex`
  based on how you want the target file named.
