# My name is Vitaly Shcherbinov.
## My contact:
* [LinkedIn](https://www.linkedin.com/in/shcherbinovv)
* [Tg](https://t.me/Vshcherbinov)
## About me:
I am a ***Junior Unity*** developer with experience in C#, OOP, and design patterns. I am currently working at a programming school and a game development studio, where I have honed my skills and gained experience in the field. I am looking for opportunities to continue my professional development and work on exciting projects as a remote Unity developer.




## Skills:
* Unity development
* C# programming
* Object-oriented programming (OOP)
* Design patterns such as SOLID

## Additional skills:
* Experience with development tools such as Rider

## Experience
* GameDev Academy
* GameDev Studio

## Preference
* Remote work

## Code example:
Move the first letter of each word to the end of it, then add "ay" to the end of the word. Leave punctuation marks untouched.
``` C#
public string PigIt(string str)
{
    var words = str.Split(' ');
        
    for (var i = 0; i < words.Length; i++)
    {
        if (!char.IsLetter(words[i][0]))
        {
            continue;
        }
            
        words[i] = words[i].Substring(1) + words[i][0] + "ay";
    }

    var result = string.Join(" ", words);
    return result;
}
```

## Languages
* Russian 
* English
