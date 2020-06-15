Codeforces API [![License](https://img.shields.io/github/license/VadVergasov/CodeforcesApiPy)](https://github.com/VadVergasov/CodeforcesApiPy/blob/master/README.md) [![Stars](https://img.shields.io/github/stars/VadVergasov/CodeforcesApiPy)](https://github.com/VadVergasov/CodeforcesApiPy/stargazers) [![Forks](https://img.shields.io/github/forks/VadVergasov/CodeforcesApiPy)](https://github.com/VadVergasov/CodeforcesApiPy/network/members) [![Issues](https://img.shields.io/github/issues/VadVergasov/CodeforcesApiPy)](https://github.com/VadVergasov/CodeforcesApiPy/issues)
==========

Installing
----------

With pip:

```bash
pip install CodeforcesApiPy
```

From the repository:

```bash
git clone https://github.com/VadVergasov/CodeforcesApiPy.git
cd codeforcesapipy
python3 setup.py install
```

Using
---------

```python
import codeforces_api

cf_api = codeforces_api.CodeforcesApi(api_key, secret) #Authorized access.
anonim_cf_api = codeforces_api.CodeforcesApi() #Unauthorized access.

parser = codeforces_api.CodeforcesParser() #Parse some info.
```

Examples
---------

Here are some examples of using this library:

* [A2OJ](https://github.com/subodhk01/a2oj) by subodhk01 - allows you to look at your ladder progress.
