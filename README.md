# MLE xoueaw 2025-04

Here we learn...
it is based on this repositoy by alexey: https://github.com/alexeygrigorev/ml-engineering-contsructor-workshop


##how to install UV

curl -LsSf https://astral.sh/uv/install.sh | sh

## DAy1

-create a folder named day_1
in the console run cd day_1 to change the current directory to be day_1
run "uv init --python 3.10"
run uv sync

## lets install the dependencies
run uv add scikit-learn==1.2.2 pandas pyarrow
run uv add --dev jupyter seaborn
run uv add numpy==1.26.4