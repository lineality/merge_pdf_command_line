## merge_pdf_rpm_linux


#### Command line code to combine two PDF files, using RPM linux such as Fedora, Redhat, Centos, etc.:

# Install

### RPM e.g. Fedora
```
$ sudo dnf install qpdf
```

### MacOS
```
$ brew install qpdf
```

### Debian e.g. Ubuntu
```
$ sudo apt install qpdf
```

# Merge PDF Files
```
$ qpdf --empty --pages YOUR_FIRST.pdf YOUR_SECOND.pdf -- NAME_OF_NEW_COMBINED_FILE.pdf
```
