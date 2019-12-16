This repository houses my personal resume, generated programmatically
following the JSON Resume schema:
https://jsonresume.org/schema/

Instructions to export resume to PDF.

-- The resume is housed in resume.json.
-- There is a command line interface to JSONresume.

  Export resume:
  >>resume export resume.json --theme onepage

  Install themes.
  >>sudo npm install -g jsonresume-theme-onepage

  Validate against JSON Resume Schema:
  >> sudo pip install json-spec
  >> json validate --schema-file=schema.json < data.json

