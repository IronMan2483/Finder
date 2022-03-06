# Finder

This notebook is about typical challenges when you have a large dataset and need to find the name of a specific customer, an address or want to filter for a defined date or period.

So one typical business case could be a client in your address list and you are not sure if this person or company is one or several times in your dataset, which will result in e.g.

* extra costs when you send out Marketing material, catalogues or presents,
* look unprofessional and you could risk to lose this contact,
* more unused space in your datasets or "file corpses"
* multiple invoices, different customer numbers and also multiple employees responsible for the same customer


![office](http://3.bp.blogspot.com/-yAMJlmzDJ7g/WueHhAx5M_I/AAAAAAAASPo/2Nnv3AKKS_gUMvrxdic6EILql9XYOY4dQCK4BGAYYCw/s1600/Sessame-TakeYourMuppetToWorkDay.JPG)

---

## __Files__

Notebook: [ipynb](https://github.com/IronMan2483/Finder/blob/main/Notebook.ipynb)

Dataset: The used [file](https://github.com/IronMan2483/Finder/blob/main/MCU_movies_Dataset.csv) is from [Kaggle](https://www.kaggle.com/prashantk93/marvel-cinematic-universe-movies-dataset?select=MCU_movies_Dataset.csv)


---

## __Technical preparation__


### __Requirements__

pyenv
python==3.9.4
Setup

For this purpose you use following commands:

````
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt

````
