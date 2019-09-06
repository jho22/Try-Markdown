# Try-Markdown

Experimenting with Markdown documents. You can make text **bold** by enclosing it in double-asterix, or you can make it *italic* by enslosing it in single-asterix.

You can identify a short in-line code snippet by enclosing it in single-back-tic characters, like so: `git init`.

You can also create lists by using the single dash followed by a space for each line of text. So far, we've covered

- **bold** text
- *italic* text
 - some `code` samples
 - simple lists
 
 Here is a sample of some C# code in what is called a "fenced block". These are created by enclosing multiple lines of text inside triple back-tics, with the first set of triple-back-tics including a reference to the programming language (for syntax highlighting)

```csharp
public static void Main(string[] args)
{
    // The canonical "first program"
    Console.WriteLine("Hellow World");
}
```

This is a really good way to make useful notes. 😁

## Making Commits

The key to using markdown and git for taking notes or doing any kind of software development is to 

- Make frequent commits
- Use meaningful messages in your commits

It takes a bit of discipline, but it pays off in the end

![Commit Messages](https://imgs.xkcd.com/comics/git_commit.png)