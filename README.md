# Mímir
Mímir is a command-line tool that is designed to scrape news articles and studies from PubMed and convert 
them to audio for offline listening. It's named after Mímir, a figure in Norse mythology that's associated with 
wisdom and knowledge.

## Features
- Mirmir can download articles from various websites and convert them to MP3s.
- Mirmir can search for studies on PubMed and convert them to MP3 files. It can also download articles from an URL.

## Requirements
- Python 3.12.10.
- FFmpeg.
- Internet connection.
- Windows 10 or later.

## Installation 
To download Mirmir, first download Mirmir from Github:
```powershell
git clone https://github.com/AJYule/Mirmir.git
```

Then go into Mirmir's directory:
```powershell
cd Mirmir
```

Create a virtual environment, and then active it:
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

Lastly, install the project:
```powershell
pip install -e .
```

## License
Mirmir is licensed under the MIT license. 