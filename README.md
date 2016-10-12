## Codewars CLI

Command line interface for the website www.codewars.com. See <https://dev.codewars.com/#api-reference> for more details. To submit answers you need your API access token which is near the bottom of your [Account Settings](https://www.codewars.com/users/edit).

### Commands

Get description of Kata.

`codewars desc KATA`

Start training a Kata.

`codewars train [KATA]`

Sumbit code in FILE to currently training Kata.

```codewars submit FILE```

Finalize submitted solution.

```codewars finalize```

Save your arguments and API key in ~/.config/codewars

```codewars register API-KEY```

### Arguments

Specify training language.

```-l --language=LANG```

Specify search strategy for train command.

```-s --strategy=STRATEGY```
