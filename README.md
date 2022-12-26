# diffuzers

A web ui for [🤗 diffusers](https://github.com/huggingface/diffusers).

< under development, request features using issues, prs not accepted atm >

## Installation

To install bleeding edge version of diffuzers, clone the repo and install it using pip.

```bash
git clone https://github.com/abhishekkrthakur/diffuzers
cd diffuzers
pip install -e .
```

Installation using pip:
    
```bash 
pip install diffuzers
```

## Usage

To run the web app, run the following command:

```bash
diffuzers run --model <path to model> --output_path <path to output folder>
``` 
    
For example, to run the web app for the [stable diffusion 2.1](https://huggingface.co/stabilityai/stable-diffusion-2-1) model, run the following command:


```bash
diffuzers run --model stabilityai/stable-diffusion-2-1 --output_path .
```

```bash
❯ diffuzers run --help
usage: diffuzers <command> [<args>] run [-h] --model MODEL --output_path OUTPUT_PATH [--share] [--port PORT]
                                        [--host HOST]

✨ Run diffuzers app

optional arguments:
  -h, --help            show this help message and exit
  --model MODEL         Path to model
  --output_path OUTPUT_PATH
                        Output path
  --share               Share the app
  --port PORT           Port to run the app on
  --host HOST           Host to run the app on
```