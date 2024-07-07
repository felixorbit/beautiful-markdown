## Badge
> Made by [shields.io](https://shields.io/badges/static-badge)

![Static Badge](https://img.shields.io/badge/markdown-badge-blue?logo=dependabot)

## Equations

> Latex support required.

Inline mode: 

$a^2 + b^2 = c^2$

```markdown
$a^2 + b^2 = c^2$
```

Block mode:

$$\frac{x}{1+x} \le ln(1+x) \le x$$

$$\frac{x_1 + \cdots + x_n}{n} \ge \sqrt[n]{x_1 \cdots x_n} \ge \frac{n}{\frac{1}{x_1} + \cdots + \frac{1}{x_n}}$$

```markdown
$$\frac{x}{1+x} \le ln(1+x) \le x$$

$$\frac{x_1 + \cdots + x_n}{n} \ge \sqrt[n]{x_1 \cdots x_n} \ge \frac{n}{\frac{1}{x_1} + \cdots + \frac{1}{x_n}}$$
```

## Diagrams

### ASCIIFlow

> Drawn with [ASCIIFlow](https://asciiflow.com/) 

```
┌──────┐            ┌──────┐
│      │            │      │
│  TL  ├───────────►│  TR  │
│      │            │      │
└──────┘            └───┬──┘
   ▲                    │
   │                    ▼
┌──┴───┐            ┌──────┐
│      │            │      │
│  BL  │◄───────────┤  BR  │
│      │            │      │
└──────┘            └──────┘
```

### Mermaid

> Draw with [Mermaid](https://mermaid.js.org/syntax/flowchart.html)

#### Flowchart

```mermaid
flowchart LR
    A(Action) --- B
    A -.- C
    B --> D
    C -.-> D
    D == get ==> E([End])
```

```
flowchart LR
    A(Action) --- B
    A -.- C
    B --> D
    C -.-> D
    D == get ==> E([End])
```

#### Class Diagram

```mermaid
classDiagram
    direction LR
    class A {
        <<interface>>
        +GetName()
    }
    class B {
        -string name
        -C c
        +GetName(D d)
    }
    class C {
        -int id
        +SetID()
    }
    class D {
        -string lan
    }
    A <|.. B
    B *-- C
    B ..> D
```

```
classDiagram
    direction TD
    class A {
        <<interface>>
        +GetName()
    }
    class B {
        -string name
        -C c
        +GetName(D d)
    }
    class C {
        -int id
        +SetID()
    }
    class D {
        -string lan
    }
    A <|.. B
    B *-- C
    B ..> D
```

### Sequence Diagram

```mermaid
sequenceDiagram
    autonumber
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts!
    John-->>Alice: Great!
```

```
sequenceDiagram
    autonumber
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts!
    John-->>Alice: Great!
```

### XYChart

```mermaid
xychart-beta
    title "Sales Revenue"
    x-axis [jan, feb, mar, apr, may, jun, jul, aug, sep, oct, nov, dec]
    y-axis "Revenue (in $)" 4000 --> 11000
    bar [5000, 6000, 7500, 8200, 9500, 10500, 11000, 10200, 9200, 8500, 7000, 6000]
    line [5000, 6000, 7500, 8200, 9500, 10500, 11000, 10200, 9200, 8500, 7000, 6000]

```

### Block Diagram

```mermaid
block-beta
  columns 3
  %% blocks that span multiple columns
  a:3
  block:group1:2
    columns 2
    h i j k
  end
  g:1
  block:group2:3
    %% columns auto (default)
    l m n o p q r z
  end
```

```
block-beta
  columns 3
  %% blocks that span multiple columns
  a:3
  block:group1:2
    columns 2
    h i j k
  end
  g:1
  block:group2:3
    %% columns auto (default)
    l m n o p q r z
  end
```

## Special Symbols

| symbol    | code       | symbol   | code       | symbol    | code       | symbol   | code       |
|-----------|------------|----------|------------|-----------|------------|----------|------------|
|  &amp;    | `&amp;`    | &darr;   | `&darr;`   |  &supe;   | `&supe;`   | &cent;   | `&cent;`   |
|  &lt;     | `&lt;`     | &harr;   | `&harr;`   |  &sube;   | `&sube;`   | &pound;  | `&pound;`  |
|  &gt;     | `&gt;`     | &varr;   | `&varr;`   |  &nsub;   | `&nsub;`   | &frac12; | `&frac12;` |
|  &nbsp;   | `&nbsp;`   | &crarr;  | `&crarr;`  |  &sup;    | `&sup;`    | &frac14; | `&frac14;` |
|  &iquest; | `&iquest;` | &lArr;   | `&lArr;`   |  &sub;    | `&sub;`    | &permil; | `&permil;` |
|  &quest;  | `&quest;`  | &rArr;   | `&rArr;`   |  &cap;    | `&cap;`    | &there4; | `&there4;` |
|  &laquo;  | `&laquo;`  | &uArr;   | `&uArr;`   |  &cup;    | `&cup;`    | &pi;     | `&pi;`     |
|  &raquo;  | `&raquo;`  | &dArr;   | `&dArr;`   |  &fnof;   | `&fnof;`   | &sup1;   | `&sup1;`   |
|  &quot;   | `&quot;`   | &hArr;   | `&hArr;`   |  &radic;  | `&radic;`  | &alpha;  | `&alpha;`  |
|  &lsquo;  | `&lsquo;`  | &vArr;   | `&vArr;`   |  &infin;  | `&infin;`  | &beta;   | `&beta;`   |
|  &rsquo;  | `&rsquo;`  | &spades; | `&spades;` |  &deg;    | `&deg;`    | &gamma;  | `&gamma;`  |
|  &ldquo;  | `&ldquo;`  | &hearts; | `&hearts;` |  &ne;     | `&ne;`     | &delta;  | `&delta;`  |
|  &rdquo;  | `&rdquo;`  | &clubs;  | `&clubs;`  |  &equiv;  | `&equiv;`  | &theta;  | `&theta;`  |
|  &para;   | `&para;`   | &diams;  | `&diams;`  |  &le;     | `&le;`     | &lambda; | `&lambda;` |
|  &sect;   | `&sect;`   | &loz;    | `&loz;`    |  &ge;     | `&ge;`     | &sigma;  | `&sigma;`  |
|  &times;  | `&times;`  | &copy;   | `&copy;`   |  &perp;   | `&perp;`   | &tau;    | `&tau;`    |
|  &divide; | `&divide;` | &reg;    | `&reg;`    |  &larr;   | `&larr;`   | &dagger; | `&dagger;` |
|  &plusmn; | `&plusmn;` | &trade;  | `&trade;`  |  &rarr;   | `&rarr;`   | &Dagger; | `&Dagger;` |
|  &otimes; | `&otimes;` | &yen;    | `&yen;`    |  &uarr;   | `&uarr;`   |          |            |
|  &oplus;  | `&oplus;`  | &euro;   | `&euro;`   |

## *Unicode Character Code

| symbol    | code        | symbol    | code        | symbol    | code        | symbol    | code        |
|-----------|-------------|-----------|-------------|-----------|-------------|-----------|-------------|
| &#10000;  | `&#10000;`  | &#10048;  | `&#10048;`  | &#10022;  | `&#10022;`  | &#10085;  | `&#10085;`  |
| &#10004;  | `&#10004;`  | &#10063;  | `&#10063;`  | &#10024;  | `&#10024;`  | &#10102;  | `&#10102;`  |
| &#10008;  | `&#10008;`  | &#10070;  | `&#10070;`  | &#10025;  | `&#10025;`  | &#10112;  | `&#10112;`  |
| &#10017;  | `&#10017;`  | &#10084;  | `&#10084;`  | &#10029;  | `&#10029;`  | &#128514; | `&#128514;` |


> *: Just a selection of interesting examples
>
> For more unicode character encoding please visit the site [Unicode Character Code Charts](https://www.unicode.org/charts/).
>
> Note that the syntax here uses decimal numbers.
