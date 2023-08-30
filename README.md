# openalex-quantum-technologies

First run the notebook **quantum2d.ipynb** to create the data files:

* quantumcentroids2d.pkl
* quantumdfinfo2d.pkl
* quantumdftriple2d.pkl
* source_page_dict.pkl

Compress the first three with

```
>gzip -k filename.pkl
```

To run the streamlist app:

```
>streamlit run quantum2d.py
```

