## 文言 / wenyan‑lang

Programming Language with chinese characters that compiles to Ruby Code

## Install
npm install -g @wenyanlang/cli

## Run
Create new file: culturebot.wy with the following content:

```
吾有一數。曰三。名之曰「甲」。
	吾有一言。曰「「問天地好在。」」。書之。
云云。
```

Run this command to run it:
```
wenyan helloworld.wy

問天地好在。
問天地好在。
問天地好在。
```

## Compile to ruby
```
wenyan -c helloworld.wy --lang=rb -o helloworld.rb
ruby helloworld.rb

問天地好在。
問天地好在。
問天地好在。
```


