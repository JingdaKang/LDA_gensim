# LDA Topic Modeling with Gensim

Two topic-modeling examples: Chinese news analysis and analysis of the Hillary Clinton email corpus. The project includes Python scripts, notebooks, input datasets, and stopword lists.

Original Chinese documentation: [README.zh-CN.md](README.zh-CN.md).

## Requirements

Python 3, gensim, jieba, NumPy, and pandas. Jupyter is optional for notebooks. Dependency versions are not pinned; the examples were written against historical Gensim APIs.

## Getting started

```sh
python -m venv .venv
# Activate .venv, then:
python -m pip install gensim jieba numpy pandas
cd 新闻主题分析
python LDA.py
```

## Project structure

| Path | Purpose |
| --- | --- |
| `新闻主题分析` | Chinese news LDA example and corpus |
| `希拉里邮件门` | Email LDA example and corpus |

## Configuration and limitations

Run each script from its own directory because dataset and stopword paths are relative. Modern Gensim/SciPy releases may require compatibility changes; installation alone is not a verified reproduction. Scripts can generate or overwrite preprocessing outputs.

## Development and validation

Inspect printed topics and example document-topic distributions. There is no automated test suite or pinned reproducibility environment.

## License

No root-level license file is included. Check source-specific notices and obtain permission before redistribution or reuse.
