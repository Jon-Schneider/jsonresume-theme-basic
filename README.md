# jsonresume-theme-onepage

A compact theme for JSON Resume, designed for printing. 

It's based on the Microsoft Word resume template I've been using since college.

## Example

http://themes.jsonresume.org/theme/onepage

## Running

Clone this repo and cd into it, then run:

```
sudo npm install -g resume-cli
resume serve --theme .
```
You can print directly from the served html.

## Options

For the "experience" and "skills" sections, you can optionally replace the "highlights" list with a "details" list with this format:

```
"details": [
  { "text": "Javascript", "comment": "expert" },
  { "text": "Coffeescript", "comment": "expert" },
  { "text": "Ruby", "comment": "competent" },
  { "text": "Java", "comment": "novice" }
]
```

See included resume.json for more details.

