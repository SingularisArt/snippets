# Custom UltiSnippets

## Ada Snippets

## All Snippets

## Bib Snippets

## Bindzone Snippets

## Blade Snippets

## Coffee-jasmine Snippets

## Coffee-react Snippets

## Coffee Snippets

## Cpp Snippets

## Crystal Snippets

## C Snippets

## Cs Snippets

## Css Snippets

## Cuda Snippets

## Django Snippets

## D Snippets

## Eelixir Snippets

## Ejs Snippets

## Elm Snippets

## Erlang Snippets

## Eruby Snippets

## Gitcommit Snippets

## Go Snippets

## Haskell Snippets

## Help Snippets

## Htmldjango Snippets

## Htmljinja Snippets

## Html_minimal Snippets

## Html Snippets

## Javascript-angular Snippets

## Javascript-ember Snippets

## Javascript-jasmine-arrow Snippets

## Javascript-jsdoc Snippets

## Javascript-node Snippets

## Javascript_react Snippets

## Javascript Snippets

## Java Snippets

## Jinja2 Snippets

## Json Snippets

## Julia Snippets

## Ledger Snippets

## Lhaskell Snippets

## Lua Snippets

## Mail Snippets

## Mako Snippets

## Markdown Snippets

## Matlab Snippets

## Objc Snippets

## Ocaml Snippets

## Octave Snippets

## Pandoc Snippets

## Perl Snippets

## Php-laravel Snippets

## Php-phpspec Snippets

## Php Snippets

## Php-symfony2 Snippets

## Plaintex Snippets

You can view the snippet [here](./plaintex.snippets)

### Environments

* `beg`:      Opens the **Begin/End** environment.
* `doc`:      Opens the **Main document** environment.
* `cnt`:      Opens the **Center** environment.
* `desc`:     Opens the **Description** environment.
* `lemma`:    Opens the **Lemma** environment.
* `prop`:     Opens the **Proposition** environment
* `thrm`:     Opens the **Theorem** environment.
* `post`:     Opens the **Postulate** environment.
* `prf`:      Opens the **Proof** environment.
* `def`:      Opens the **Definition** environment.
* `nte`:      Opens the **Note** environment.
* `prob`:     Opens the **Problem** environment.
* `corl`:     Opens the **Corollary** environment.
* `exm`:      Opens the **Example** environment.
* `ntn`:      Opens the **Notion** environment.
* `rep`:      Opens the **Repetition** environment.
* `prop`:     Opens the **Proposition** environment.
* `int`:      Opens the **Intuition** environment.
* `obs`:      Opens the **Observation** environment.
* `conc`:     Opens the **Conclusion** environment.
* `enum`:     Opens the **Enumerate** environment.
* `item`:     Opens the **Itemize** environment.
* `case`:     Opens the **Cases** environment.
* `ali`:      Opens the **Align** environment.
* `eqt`:      Opens the **Equation** environment.
* `fig`:      Opens the **Figure** environment.
* `grp`:      Opens the **Graph** environment.
* `tbl`:      Opens the **Table** environment.     

### Math

#### Inline and Display Math

* `im`:     Opens the **Inline Math** environment. ($$)
* `dm`:     Opens the **Display Math** environment. (\[\])

#### Fast Math Typing

* `=>`:     Implied By.
* `|->`:    Mapsto.
* `+-`:     Plus Minus.
* `-+`:     Minus Plus.
* `\*`:     Times.
* `-:-`:    Divide.
* `...`:    Straight dots.
* `.v`:     Vertical dots.
* `.a`:     Dots above line.
* `:.`:     Therefore.

#### Equality

* `<<`:     Less than.
* `>>`:     Greater than.
* `<=`:     Less than or equal to.
* `>=`:     Greater than or equal to.
* `!=`:     Not equal to.
* `~=`:     Approximately.
* `===`:    Equivalent.
* `def=`:   Defeq.

#### Other math symbols

* `oo`:     Infinity.
* `oc`:     Proportional.

#### Sub and Superscripts

* `x1`:       This will change to `x_1`. You can replace `x` with any variable
  and `1` with any number. 
* `x_11`:     This will change to `x_{11}`. You can replace `x` with any
  variable and `1` with any number.
* `x_{11}1`:  This will change to `x_{111}`. You can replace `x` with any
  variable and `1` with any number.
* `sq`:       ^2.
* `cb`:       ^3.
* `compl`:    ^{c}.
* `td`:       ^{}.
* `inv`:      ^{-1}.
* `sr`:       \sqrt{}
* `nr`:       \sqrt[]{}

#### Fractions

* `//`:       \frac{}{}.
* `1/`:       \frac{1}{}.

#### Over text type

* `bar`:      \overline{}.
* `xbar`:     \overline{a}. You can replace `x` with any letter.
* `hat`:      \hat{}.
* `xhat`:     \hat{x}. You can replace `x` with any letter.
* `xdot`:     \dot{x}. You can replace `x` with any letter.
* `x.,`:      \vec{x}. You can replace `x` with any letter(s).
* `x,.`:      \vec{x}. You can replace `x` with any letter(s).

#### Sums and products

* `sum`:      \sum_{}^{}.
* `prod`:     \prod_{}^{}.
* `taylor`:   \sum_{n=0}^{\infty} \frac{f^{(n)}(0) \cdot x^n}{n!}$0.

#### Calculus

* `int`:      \int d.
* `dint`:     \int_{}^{}  dx.
* `lim`:      \lim_{ \to }.
* `odx`:      \od{}{x}.
* `ody`:      \od{}{y}.
* `odt`:      \od{}{t}.
* `od`:       \od[]{}{}.
* `pd`:       \pd[]{}{}.
* `md`:       \md{}{}.
* `eval`:     \eval{}\_{}^{}.
* `nab`:      \nabla.
* `grad`:     \nabla.

#### Matrices and Vectors

* `mat`:      Create **bmatrix** environment.
* `det`:      Create **vmatrix** environment.
* `vec`:      Create **pmatrix** environment.
* `matil`:    Create **smallmatrix** environment.
* `detil`:    Create **smallmatrix** environment.
* `vecil`:    Create **smallmatrix** environment.
* `choose`:   { \choose }.

#### (), [], {}, and their bigger counterparts

* `()`:       \left(\right).
* `{}`:       \left{\right}.
* `[]`:       \left[\right].
* `(`:        \left(.
* `)`:        \right).
* `{`:        \left{.
* `}`:        \right}.
* `[`:        \left[.
* `]`:        \right].

#### QED and QEA

* `qed`:      Q.E.D.
* `qea`:      Q.E.A.

### Lessons

* `les`:      \lesson{}{}{}{}.
* `lec`:      \lesson{}{}{}.

### Sections

* `chap`:     Create a **chapter** with a label.
* `sec`:      Create a **section** with a label.
* `sec*`:     Create an unnumbered **section** with a label.
* `sub`:      Create a **subsection** with a label.
* `sub*`:     Create an unnumbered **subsection** with a label.
* `subsub`:   Create a **subsubsection** with a label.
* `subsub*`:  Create an unnumbered **subsubsection** with a label.
* `par`:      Create a **paragraph** with a label.
* `par*`:     Create an unnumbered **paragraph** with a label.
* `subpar`:   Create a **subparagraph** with a label.
* `subpar*`:  Create an unnumbered **subparagraph** with a label.

### Other

* `date`:     Example: Feb 20 2022 Sun (13:00:39).
* `sign`:     Create your signature.
* `ref`:      Create a reference.
* `link`:     \hyperlink{}{}.
* `newp`:     \newpage.

## Plsql Snippets

## Proto Snippets

## Puppet Snippets

## Python Snippets

## Rails Snippets

## Rnoweb Snippets

## Robot Snippets

## R Snippets

## Rst Snippets

## Ruby Snippets

## Rust Snippets

## Sh Snippets

## Snippets Snippets

## Soy Snippets

## Supercollider Snippets

## Svelte Snippets

## Tcl Snippets

## Typescript_react Snippets

## Typescript Snippets

## Vim Snippets

## Vue Snippets

## Xhtml Snippets

## Xml Snippets

## Zsh Snippets

