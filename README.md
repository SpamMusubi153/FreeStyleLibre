# FreeStyle Libre
Export and visualize your FreeStyle Libre Glucose Level Data

---

My grandmother has diabetes. At the end of 2023, difficulties in monitering blood glucose levels led to a hospitilization for diabetic ketoacidosis, sepsis, and other diabetes-related complications. Fortunately, she is recovering now, and is using a trial of a FreeStyle Libre system to more closely moniter her glucose levels.

With my deep machine learning (ML) background, the possibility of having data to work with excited me. I started thinking of ways to tie it with nutritional data to predict trends and the volume of insulin dosages. Unfortunately, I soon realized that the data the FreeStyle Libre system collects **isn't easily portable**, and even **seems to be stored for a limited amount of time**. 

Thanks to [Selcuk Kekec's](https://github.com/khskekec) work documenting the [LibreLinkUp API,](https://gist.github.com/khskekec/6c13ba01b10d3018d816706a32ae8ab2) I started working on a few different ways to automatically fetch, record, visualize, and process data beyond what is offered by the product's native apps. I am pubishing some of my work here so that other interested individuals might be able to benefit from enhanced access to their own data.

I will be working on sharing my work shortly.

### Data Collection

| | Python Script | Apple Shortcuts Collection | Web App |
| --- | --- | --- | --- |
| Fetch All Data (Logbook and Graph Data) | ✅ | ✅ | ❌ |
| Remove Duplicate Data | ✅ | ❌ | ❌ |
| Save Data | ✅ | ✅ | ❌ |
| Ready for Use? | Almost! | Almost! | ❌ |


### Data Visualization
| | Jupyter Notebook |
| --- | --- |
| Create a Scatterplot of Data | ✅ |
| Differentiate Logbook and Graph Data | ✅ |
| Preserve Measurement Colors | ✅ |
| Graph Alarm Events | ✅ |
| Graph Trend Directions | ✅ |
| Graph Nights | ✅ |
| Graph Custom Ranges | ✅ |
| User-Friendly Interface | ❌ |

### Machine Learning Data Processing

ML model training is in progress.

---

Thank you for stopping by! At this time, I am still working through college. If you found this project helpful, I would appreciate any support you are able to lend.

<noscript><a href="https://liberapay.com/MusubiToTheMax/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
