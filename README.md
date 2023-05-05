# Surveys

File structure is normalized to allow retrieving surveys from the Devographics app (surveyform, results, API...)
```
|__<surveyId>
|_____files common to all editions (years) of a survey
|_____<editionId>
|________files for this specific edition
|__surveyParamsTable.json: maps URL slug to surveyId and editionId
```