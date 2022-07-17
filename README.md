A single-page, one-column resume. It uses the base latex templates and fonts to provide ease of use and installation when trying to update the resume. The different sections are clearly documented and custom commands are used to provide consistent formatting. The three main sections in the resume are

*   Skiils and Competencies
*   Experience
*   Education
*   Activities and Organizations

### Motivation

I created this template as managing a resume on Google Docs was hard and changing any formatting was too difficult since it had to be applied in multiple places. Most currently available templates either focus on two columns, or are multiple pages long. I personally found the two-column templates hard to focus while multiple-page resumes were just too long to be used in career fairs.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex sourabh_bajaj_resume.tex
```

### License
Format is MIT but all the data is owned by Neil John Ortega.
