# sir-model
## Repository Title
### About This Project

### Repository Structure

### Built With
- [Python version 3.11.0](https://www.python.org/downloads/)
- [`{poetry}`](https://python-poetry.org/docs/) for package management
### Getting Started
## uses fractonal data
### Usage

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

### Contact

### Acknowledgements

### Test model typically would want to give more detail like what an sir model is

```math
\begin{align}
\frac{dS}{dt} &= \mu (N - S) -\beta S \frac{I}{N} \\
\frac{dI}{dt} &= \beta S \frac{I}{N} - \gamma I - \mu I \\
\frac{dR}{dt} &= \gamma I - \mu R
\end{align}
```

```math
\begin{align}
\mu &= \frac{1}{50*52} \\
\beta &= 2 \\
\gamma &= \frac{1}{2} \\\\

N &= 1000 \\
S_0 &= 999.0 \\
I_0 &= 1.0 \\
R_0 &= 0.0
\end{align}
```
```
.
├── data/
├── figs/
├── funs/
├── out/
└── src/
```

- `data/` contains ...
- `figs/` contains ...
- `funs/` contains ...
- `out/` contains ...
- `src/` contains ...
poetry --version
- 