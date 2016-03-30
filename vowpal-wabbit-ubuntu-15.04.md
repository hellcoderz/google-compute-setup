sudo apt-get update
sudo apt-get install build-essential zlib1g-dev libtool autoconf automake libboost-python-dev libboost-program-options-dev
git clone https://github.com/JohnLangford/vowpal_wabbit.git
cd vowpal_wabbit
make
make python
cd python
python test_search.py
