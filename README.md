## Vocabulary Journal


### Features & Functionality
* Able to read and write to JSON
* Locally store journal of words and definitions learned
* Randomly produce words for learning
* Prompts to add words and definitions --> JSON
* Export to CSV
* Integration with Dictionary API or word data somewhere to consume/lookup

### Structure
```
{
    "word": "Assuage",
    "definitions": [
        {
            "part_of_speech": "verb",
            "definition": "make (an unpleasant feeling) less intense",
            "synonyms": ["relieve", "ease", "alleviate", "sooth", "mitigate", "satisfy", "appease"],
            "examples": ["Something that a nurse might assuage is someone's pain with the distribution of medicine", "The letter assuaged the fears of most members"]
        },
        {
            "part_of_speech": "verb",
            "definition": "satisfy (an appetite or desire)",
            "synonyms": ["relieve", "ease", "alleviate", "sooth", "mitigate", "satisfy", "appease"],
            "examples": ["Something that a nurse might assuage is someone's pain with the distribution of medicine", "The letter assuaged the fears of most members"] 
        }
    ]
}
```
