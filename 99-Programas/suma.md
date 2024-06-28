| Número de Línea | Lexema             | Token              |
|-----------------|--------------------|--------------------|
| 5               | int                | palabraReservada   |
| 5               | esNumero           | identificador      |
| 5               | (                  | caracterPuntuación |
| 5               | const              | palabraReservada   |
| 5               | char               | palabraReservada   |
| 5               | *                  | operador           |
| 5               | nro                | identificador      |
| 5               | )                  | caracterPuntuación |
| 5               | {                  | caracterPuntuación |
| 6               | while              | palabraReservada   |
| 6               | (                  | caracterPuntuación |
| 6               | *                  | operador           |
| 6               | nro                | identificador      |
| 6               | )                  | operador           |
| 6               | {                  | caracterPuntuación |
| 7               | if                 | palabraReservada   |
| 7               | (                  | operador           |
| 7               | !                  | operador           |
| 7               | isdigit            | palabraReservada   |
| 7               | (                  | operador           |
| 7               | *                  | operador           |
| 7               | nro                | identificador      |
| 7               | )                  | operador           |
| 7               | )                  | operador           |
| 7               | {                  | caracterPuntuación |
| 8               | return             | palabraReservada   |
| 8               | 0                  | constante          |
| 8               | ;                  | caracterPuntuación |
| 9               | }                  | caracterPuntuación |
| 10              | nro                | identificador      |
| 10              | +                  | operador           |
| 10              | +                  | operador           |
| 10              | ;                  | caracterPuntuación |
| 11              | }                  | caracterPuntuación |
| 12              | return             | palabraReservada   |
| 12              | 1                  | constante          |
| 12              | ;                  | caracterPuntuación |
| 15              | int                | palabraReservada   |
| 15              | main               | palabraReservada   |
| 15              | (                  | operador           |
| 15              | int                | palabraReservada   |
| 15              | argc               | palabraReservada   |
| 15              | ,                  | operador           |
| 15              | char               | palabraReservada   |
| 15              | *                  | operador           |
| 15              | *                  | operador           |
| 15              | argv               | palabraReservada   |
| 15              | )                  | operador           |
| 15              | {                  | caracterPuntuación |
| 16              | if                 | palabraReservada   |
| 16              | (                  | operador           |
| 16              | argc               | palabraReservada   |
| 16              | !                  | operador           |
| 16              | =                  | operador           |
| 16              | 3                  | constante          |
| 16              | )                  | operador           |
| 16              | {                  | caracterPuntuación |
| 17              | puts               | palabraReservada   |
| 17              | (                  | operador           |
| 17              | "uso: suma nro1 nro2" | literalCadena      |
| 17              | )                  | operador           |
| 17              | ;                  | caracterPuntuación |
| 18              | exit               | palabraReservada   |
| 18              | (                  | operador           |
| 18              | 0                  | constante          |
| 18              | )                  | operador           |
| 18              | ;                  | caracterPuntuación |
| 19              | }                  | caracterPuntuación |
| 20              | if                 | palabraReservada   |
| 20              | (                  | operador           |
| 20              | !                  | operador           |
| 20              | esNumero           | identificador      |
| 20              | (                  | operador           |
| 20              | argv               | palabraReservada   |
| 20              | [                  | caracterPuntuación |
| 20              | 1                  | constante          |
| 20              | ]                  | caracterPuntuación |
| 20              | )                  | operador           |
| 20              | |                  | caracterPuntuación |
| 20              | |                  | caracterPuntuación |
| 20              | !                  | operador           |
| 20              | esNumero           | identificador      |
| 20              | (                  | operador           |
| 20              | argv               | palabraReservada   |
| 20              | [                  | caracterPuntuación |
| 20              | 2                  | constante          |
| 20              | ]                  | caracterPuntuación |
| 20              | )                  | operador           |
| 20              | )                  | operador           |
| 20              | {                  | caracterPuntuación |
| 21              | puts               | palabraReservada   |
| 21              | (                  | operador           |
| 21              | "nro1 y nro2 deben ser constantes numéricas" | literalCadena  |
| 21              | )                  | operador           |
| 21              | ;                  | caracterPuntuación |
| 22              | exit               | palabraReservada   |
| 22              | (                  | operador           |
| 22              | -                  | operador           |
| 22              | 1                  | constante          |
| 22              | )                  | operador           |
| 22              | ;                  | caracterPuntuación |
| 23              | }                  | caracterPuntuación |
| 24              | int                | palabraReservada   |
| 24              | sum1               | identificador      |
| 24              | =                  | operador           |
| 24              | atoi               | palabraReservada   |
| 24              | (                  | operador           |
| 24              | argv               | palabraReservada   |
| 24              | [                  | caracterPuntuación |
| 24              | 1                  | constante          |
| 24              | ]                  | caracterPuntuación |
| 24              | )                  | operador           |
| 24              | ;                  | caracterPuntuación |
| 25              | int                | palabraReservada   |
| 25              | sum2               | identificador      |
| 25              | =                  | operador           |
| 25              | atoi               | palabraReservada   |
| 25              | (                  | operador           |
| 25              | argv               | palabraReservada   |
| 25              | [                  | caracterPuntuación |
| 25              | 2                  | constante          |
| 25              | ]                  | caracterPuntuación |
| 25              | )                  | operador           |
| 25              | ;                  | caracterPuntuación |
| 26              | printf             | palabraReservada   |
| 26              | (                  | operador           |
| 26              | "la suma de        | literalCadena      |
| 26              | %d                 | caracterPuntuación |
| 26              | y                  | literalCadena      |
| 26              | %d                 | caracterPuntuación |
| 26              | es                 | literalCadena      |
| 26              | %d                 | caracterPuntuación |
| 26              | ,                  | operador           |
| 26              | sum1               | identificador      |
| 26              | sum2               | identificador      |
| 26              | ,                  | operador           |
| 26              | sum1               | identificador      |
| 26              | +                  | operador           |
| 26              | sum2               | identificador      |
| 26              | ;                  | caracterPuntuación |
| 27              | return             | palabraReservada   |
| 27              | 0                  | constante          |
| 27              | ;                  | operador           |