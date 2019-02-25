# References
- https://rasa.com/docs/nlu/0.12.0/tutorial/

## Command 1 - Create the datamodel
`python3 -m rasa_nlu.train --config config_spacy.yml --data demo-rasa.json --path projects`

## Command 2 - Run the server
`python3 -m rasa_nlu.server --path projects`

## Tool to generate the dataset
- https://rasahq.github.io/rasa-nlu-trainer/
- https://github.com/RasaHQ/rasa-nlu-trainer

## Additional package installs required
- sudo pip3 install spacy
- sudo pip3 install sklearn-crfsuite
- sudo python3 -m spacy download en