

[notes on rdf, and owl](https://docs.google.com/document/d/1N22HAKbmxAaHhpbt1FbgakUUkE1kZFIGcHOSMr0tVGw/edit)

conda create -n py37 python=3.7 matplotlib pandas scikit-learn jupyter seaborn plotly pydot nltk
conda update -n base conda
conda env list
source activate py37
pip install rdflib
pip install Owlready2

git clone https://github.com/RDFLib/rdflib
git clone https://github.com/RDFLib/OWL-RL
python setup.py install
