# Hanashi
Hanashi is a Python project designed to automate audio books and video production

## Installation

## Commands

## Documentation

### Whisper

https://github.com/openai/whisper

### Data Scraping

`pip install requests`

`get_site_data(URL: str) -> Obj`

__URL__ -> _A link to the website containing the data desired_

__Returns__ -> _An object containing the response_

`find_book(URL: str, Name: str, Deviation: float, Filter: bool = False) -> str`

__URL__ -> _A link to the website you want to search_

__Name__ -> _The name of the media you want to find_

__Deviation__ -> _A float between 0 and 1 that determines how broad the search is_

__Filter__ -> _It filters the search to 1 result_

__Returns__ -> _None if not found, Obj containing site data if Filter is set to true, or a list containing site data for all results_


### Video Compilation
