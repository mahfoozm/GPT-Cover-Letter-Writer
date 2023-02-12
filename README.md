# CoverGPT

[![PyPi](https://img.shields.io/pypi/v/CoverGPT.svg)](https://pypi.python.org/pypi/CoverGPT)
[![Downloads](https://static.pepy.tech/badge/CoverGPT)](https://pypi.python.org/pypi/CoverGPT)

Generate a personalized & formatted cover letter for a given job position utilizing your resume.

![CoverGPT](https://user-images.githubusercontent.com/95328615/218336746-7d12fbac-70a2-4125-b2a5-b93919d66169.png)

## Installation

> You will need [Python](https://www.python.org/downloads/) and a [TeX](https://www.tug.org/texlive/) distribution installed on your system.


Install with this command (enter in command prompt/terminal):
```
pip install CoverGPT
```
Run with this command:
```
python3 -m CoverGPT
```

Before generating your first cover letter, ensure that you have set your API key and filled out your user information. If you want a more personalized cover letter, upload your resume. You can still generate a cover letter without uploading your resume; but it will be of much lower quality.

### API Key
To use CoverGPT, you need a ChatGPT API key. To get one, make a ChatGPT account and go to [this link](https://platform.openai.com/account/api-keys). Generate an API key and set it in CoverGPT.

## Example
Example of a cover letter generated using CoverGPT (using the included template)

![example](https://user-images.githubusercontent.com/95328615/216749052-9fab03dc-f02a-4523-967f-e07f382618b4.png)


## Using your own cover letter template
A LaTeX template is provided, but you can use your own if you wish. If you choose to use your own template, make the following replacements in your .tex file:
- First Name: #firstName
- Last Name: #lastName
- Website Link: #websiteUrl
- Email: #email
- Phone Number: #phoneNumber
- Full Name: #fullName
- Company Name: #companyName
- Company Address: #address1
- City, State/Province, Zip/Postal Code: #address2

Insert a \vspace{0.5cm} at the bottom of your template (this is where the paragraph body will be inserted).

### TO-DO:

- considering a CoverGPT web app, for simplified usage
