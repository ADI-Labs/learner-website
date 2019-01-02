# The Learner

## Getting Started 

``` bash
virtualenv blog
```

``` bash
cd blog/
```

``` bash 
source bin/activate
```

``` bash
pip3 install -r requirements.txt
```

## Running The Code

``` bash
python3 app.py
```

### Project Layout

```
.
├── requirements.txt
├── README.md
├── scripts
│   ├── bootstrap.sh    -- Set-up PostgreSQL logic and `.env`
│   └── vagrant.sh      -- Script to setup Vagrant
└── Vagrantfile
```
