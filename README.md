# finnance

Flask React App for saving all my financial transactions etc

## dev environment

### setup

**requirements:**

- installed conda
- installed npm

```
conda env create -n finnance --file environment.yml
```

from `/frontend` dir:
```
npm i
```

### run


from `/backend` directory:
```
conda activate finnance
flask run --debug
```

from `/frontend` dir:
```
npm start
```