# AI Bootcamp - Starter Project (Java)

This is your starting template for learning to program with AI assistance. The AI will help you build working programs quickly — then you'll learn to improve them by asking the right questions.

## Setup

1. Install the JDK 21: https://adoptium.net/
   - Download the latest LTS version for your operating system.

2. Install Maven: https://maven.apache.org/download.cgi
   - Or use a package manager: `brew install maven` (Mac), `choco install maven` (Windows), `sudo apt install maven` (Linux).

3. Verify it works:
   ```
   java --version
   mvn --version
   ```

4. Compile and run the hello world:
   ```
   mvn compile exec:java -Dexec.mainClass="com.bootcamp.App"
   ```

## Using AI Tools

### Claude Code (recommended)
1. Install Claude Code: https://docs.anthropic.com/en/docs/claude-code
2. Open a terminal in this folder
3. Run `claude` and start asking it to build things

### Cursor
1. Install Cursor: https://cursor.com
2. Open this folder in Cursor
3. Use the AI chat to start building

### GitHub Copilot
1. Install the Copilot extension in VS Code
2. Open this folder in VS Code (install the Java Extension Pack)
3. Use Copilot Chat to start building

## Running Code

```
mvn compile exec:java -Dexec.mainClass="com.bootcamp.App"
```

Or compile and run directly:
```
javac -d target src/main/java/com/bootcamp/App.java
java -cp target com.bootcamp.App
```

## The Learning Process

1. Ask the AI to build something — it will give you working code
2. Run it and see that it works
3. Then ask the AI to improve it: "Add comments", "Use better variable names", "Break this into methods"
4. Learn what good code looks like by seeing the before and after

## Starting a New Project

Clone a fresh copy of this template for each new project:
```
git clone <repo-url> my-new-project
```

## Start Building!

Tell the AI what you want to build! Examples:
- "Build me a number guessing game"
- "Create a to-do list app"
- "Make a quiz program about animals"
