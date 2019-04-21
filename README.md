# conjoint_embedded_data
Embedded data for conjoint experimental designs

This is an addition to the conjoint experimental design example provided by Thomas Leeper here. It is only meant to clarify exactly how to set up embedded data on Qualtrics. 
Following this 
```js
Qualtrics.SurveyEngine.setEmbeddedData('traits1a', traits_a.join("|"));
Qualtrics.SurveyEngine.setEmbeddedData('traits1b', traits_b.join("|"));
```
Enter this in the ‘embedded data’ tab in Qualtrics:
 ![example](example.png)


