DOCD
===
This is the source code for [Dual Ontology-enhanced Clinical Decision Learning for First-admission Mortality Prediction]()


Data preparation
----
You will first need to request access for MIMIC dataset:
- [MIMIC-III](https://physionet.org/content/mimiciii/1.4/)
- [MIMIC-IV](https://physionet.org/content/mimiciv/3.1/)

Place the CSV files in the `data` directory


Model training
----
1. Install Required Libraries.
```bash
pip install -r requirements.txt
```
2. Process MIMIC data.
```bash
python DOCD_process_mimic3.py --out_path processed/
or
python DOCD_process_mimic4.py --out_path processed/
```
3. Train the model.
```bash
.\DOCD_mimic3.sh
or
.\DOCD_mimic4.sh
```

Cite
----
If you find the paper or the implementation helpful, please cite the following paper:
```

```

