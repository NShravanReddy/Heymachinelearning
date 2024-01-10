---
title: "Installing tensor flow on ARM Mac(M1/M2/M3)"
datePublished: Wed Jan 10 2024 14:09:16 GMT+0000 (Coordinated Universal Time)
cuid: clr7uwwoz001i09l5g1x78rq5
slug: installing-tensor-flow-on-arm-macm1m2m3
tags: machine-learning, tensorflow, macos

---

brew install miniforge

nshravanreddy@NSR ~ % mkdir tensorflow

nshravanreddy@NSR ~ % cd tensorflow

nshravanreddy@NSR tensorflow % conda activate env

nshravanreddy@NSR tensorflow % conda install -c apple tensorflow-deps

(env) nshravanreddy@NSR tensorflow % python -m pip install tensorflow

(env) nshravanreddy@NSR tensorflow % python -m pip install tensorflow-metal

conda install jupyter pandas numpy matplotlib scikit-learn

To install Miniforge, run the command:

```plaintext
brew install miniforge

```

Then, create a new directory called `tensorflow` by executing the following command:

```plaintext
mkdir tensorflow

```

Navigate to the `tensorflow` directory:

```plaintext
cd tensorflow

```

Activate the virtual environment named `env`:

```plaintext
conda activate env

```

Install the TensorFlow dependencies provided by Apple:

```plaintext
conda install -c apple tensorflow-deps

```

Next, install TensorFlow by running the following command:

```plaintext
python -m pip install tensorflow

```

If you are using Apple Silicon, you can also install the `tensorflow-metal` package:

```plaintext
python -m pip install tensorflow-metal

```

To install additional packages such as Jupyter, Pandas, NumPy, Matplotlib, and Scikit-learn, use the following command: