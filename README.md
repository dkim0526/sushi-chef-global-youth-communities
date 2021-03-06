# Global Youth Communities Chef

Sushi chef for `Global Youth Communities` - Import content from `Global Youth Communities` into `Kolibri Studio`


## Installation

* Install [Python 3](https://www.python.org/downloads/) if you don't have it already.

* Install [pip](https://pypi.python.org/pypi/pip) if you don't have it already.

* Create a Python virtual environment for this project (optional, but recommended):
   * Install the virtualenv package: `pip install virtualenv`
   * The next steps depends if you're using UNIX (Mac/Linux) or Windows:
      * For UNIX systems:
         * Create a virtual env called `venv` in the current directory using the
           following command: `virtualenv -p python3  venv`
         * Activate the virtualenv called `venv` by running: `source venv/bin/activate`.
           Your command prompt will change to indicate you're working inside `venv`.
      * For Windows systems:
         * Create a virtual env called `venv` in the current directory using the
           following command: `virtualenv -p C:/Python36/python.exe venv`.
           You may need to adjust the `-p` argument depending on where your version
           of Python is located.
         * Activate the virtualenv called `venv` by running: `.\venv\Scripts\activate`

* Run `pip install -r requirements.txt` to install the required python libraries.


## Usage
##### Get an Authorization Token
In order to run the script, you need an authorization token. To get one,
  1. Create an account on [Kolibri Studio](https://contentworkshop.learningequality.org/)
  2. Navigate to the Tokens tab under your Settings page
  3. Copy the given authorization token (you will need this for later).

##### Running the Chef
In `sushi-chef-global-youth-communities` directory, run the following command to run the script with token from previous step:
```
$ ./sushichef.py -v --token=<AUTHORIZATION TOKEN>

```

Example
```
$ ./sushichef.py -v --token=123456abcdefb4c9404451768a3924eb71123456
```
