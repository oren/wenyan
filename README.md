# Adoption Program 1 - Build a bot

## Step 1 - Build a command line app in Ruby

### 1. What is this?
This 10 minutes tutorial you will build a program that prints 問天地好在 (It's good to ask the world.) 3 times.

### 2. How?
You will use a programming Language called wenyan (文言) to build it.

### 3. Install the wenyan programming language (文言)

```
npm install -g @wenyanlang/cli
```

Note: You need to have npm install on your laptop

### 4. Create the wenyan program
Create new file: hello.wy with the following content:

```
吾有一數。曰三。名之曰「甲」。
	吾有一言。曰「「問天地好在。」」。書之。
云云。
```

Run this command to run it:
```
wenyan hello.wy

問天地好在。
問天地好在。
問天地好在。
```

### 5. Create the Ruby program
```
wenyan -c hello.wy --lang=rb -o hello.rb
ruby hello.rb

問天地好在。
問天地好在。
問天地好在。
```

Congrats! You build a command line app in Ruby. Move to step 2

## Step 2 - Build a command line app in Crystal

### 1. What is this?
This 10 minutes tutorial you will build a program that prints 問天地好在 3 times. This time you'll use Crystal programming language.

### 2. How?
You will use a programming called Crystal to build it.

### 3. Install Crystal
```
curl -sSL https://dist.crystal-lang.org/apt/setup.sh | sudo bash
sudo apt install crystal
```

### 4. Create a Crystal program
Create new file: hello.wy with the following content:
```
甲=3
甲.times do |_rand1|
	puts "問天地好在。"
end
```

## 5. Run it
```
crystal hello.cr

問天地好在。
問天地好在。
問天地好在。
```

## Step 3 - Run multiple apps at the same time
TODO

## Step 3 - Build a web interface for the app
TODO
