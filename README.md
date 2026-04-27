# resume
Based off of [jakegut/resume](https://github.com/jakegut/resume/) and [sb2nov/resume](https://github.com/sb2nov/resume/).

# Build using pdflatex
```
pdflatex harry-resume.tex && open harry-resume.pdf &
```

# Build using Docker
```
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex harry-resume.tex
```
