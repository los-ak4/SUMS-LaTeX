# SUMS-LaTeX
The official UR SUMS LaTeX package.

## Purpose
Creating a demonic monstrosity, duh.
More specifically, a collaborative repo to build the weirdest math preamble ever.
Think weird fonts, random character rotations, and oddly specific macros.

## Format
- Character limit per line is 90 (subject to change).
  Use multiple lines if needed.
- Every line of LaTeX must be sufficiently documented with comments before being incorporated into the repo.
- Add one-line comments immediately above the relevant line of code using `%`-comments:  
```latex
% This is a one-line comment *sufficiently* explaining the line below
\newcommand[\bruh][1]{}
```
- For multi-line comments, use the `\bruh` command (defined in the preamble itself):
```latex
\bruh{
This is a whole paragraph explaining how the code below works.
I really hope all this complicated dark magic is worth it.
}
\newcommand[\huh][0][This is a useless command, unworthy of documentation]
```

## How to contribute
- Simply submit a pull request after making sure your TeX is formatted properly :)
- Open issues whenever needed.
