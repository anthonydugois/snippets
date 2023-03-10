## Figures

### Subfigures side-by-side

```latex
\usepackage{caption}
\usepackage{subcaption}

% ...

\begin{figure}
  \centering

  \begin{subfigure}[t]{0.5\textwidth}
    \centering
    
    % fig 1
    
    \caption{}
    \label{}
  \end{subfigure}%
  \hfill%
  \begin{subfigure}[t]{0.5\textwidth}
    \centering
    
    % fig 2
    
    \caption{}
    \label{}
  \end{subfigure}

  \caption{}
  \label{}
\end{figure}
```
