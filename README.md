# Contextualized Word Embeddings


### Kratak opis projekta:

Projekat smo podelili u 3 celine (sveske):

- U uvodnoj svesci je predstavljen “[Contextual String Embeddings for Sequence Labeling](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://alanakbik.github.io/papers/coling2018.pdf)” Alan Akbik, Duncan Blythe i Roland Vollgraf 2020. i CWE model “Contextual string embeddings” predstavljen u radu. Naučnici su sve svoje modele i kod organizovali u Flair radni okvir koji je javno dostupan. Biće predstavljene i neke od osnovnih funkcionalnosti Flair radnog okvira.
- U drugoj svesci biće predstavljen način za učitavanje skupova podataka koje Flair nudi kao i opšti postupak treniranje modela za prepoznavanje upos etiketa uz korišćenje CWE modela iz radnog okvira. Model je treniran na skupu rečenica na srpskom jeziku i rezltati su prikazani na kraju sveske.
- U trećoj svesci predstavljen je postupak formiranja CWE modela nad proizvoljnim korpuson. Korišćeni su tekstovi na srpsom jeziku. Model je dalje iskorišćem za treniranje modela za prepoznavanje upos etiketa i rezultati su prikazani na kraju sveske



### Podešavanje okruženja za pokretanje projekta

`Flair` radni okvir je moguće instalirati preko `pip`-a:

```shell
pip install flair
```

> Napomena:
>
> Flair nije kompatibilan sa `Python 3.10`, već samo sa `Python 3.9.12` i na dole. Tako da u koliko imate noviju verziju Python-a, potrebno je da na bilo koji način podignete virtuelno Python okruženje. Neke od alternativa: 
>
> 1. Anaconda - https://docs.anaconda.com/anaconda/install/
> 2. Pyenv - https://github.com/pyenv/pyenv
>     - Dodatne instrukcije za instalaciju: https://realpython.com/intro-to-pyenv/

Paketi koji su neophodni za `Flair` radni okvir:

1. `pytorch`

    - https://pytorch.org/get-started/locally/

2. `numpy`

    ```shell
    pip install numpy
    ## ili
    conda install numpy
    ```

3. `pandas`

    - https://pandas.pydata.org/docs/getting_started/install.html

    ```shell
    pip install pandas
    ## ili
    conda install pandas
    ```

4. `scikit-learn`

    - https://scikit-learn.org/stable/install.html

    ```shell
    pip install scikit-learn
    ## ili
    conda install -c conda-forge scikit-learn
    ```

5. `matplotlib`

    - https://matplotlib.org/stable/users/installing/index.html

    ```shell
    pip install matplotlib
    ## ili
    conda install matplotlib
    ```

6. `seaborn`

    - https://seaborn.pydata.org/installing.html

    ```shell
    pip install seaborn
    ## ili
    conda install seaborn
    ```



### Literatura i podaci

1. Istrenirani modeli mogu se pronaći na linku:
	- https://drive.google.com/file/d/1AsFBwFFXF-Lt9agq9-mpqVu1kxMdVwl8/view?usp=sharing
	- svi modeli su sačuvani u formatu `resources/model_library/ime_modela/final-model.pt`
2. Podaci uzeti sa linka:

	- https://github.com/UniversalDependencies/UD_Serbian-SET
	
	- u pitanju su ručno labelirane rečenice na nivou tokena, na srpskom jeziku

3. Koncept i ideja za model preuzete iz naučnog rada:
    - https://alanakbik.github.io/papers/coling2018.pdf
4. Flair radni okvir preuzet sa:
    - https://github.com/flairNLP/flair



### Članovi tima

Nikola Perić 1096/2021

- GitHub: https://github.com/backspacer303

Vladimir Batoćanin 1068/2021

- GitHub: https://github.com/Vbatocanin



