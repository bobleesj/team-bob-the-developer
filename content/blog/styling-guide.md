# Markdown
The platform will automatically parse the markdown you've uploaded. Therefore, it is important to maintain the style for consistent user experience.

### Heading
- `#` for the  title
- `##` for the subtitle
- `###` and `####` for the rest of headings and sub-headings

### Image
Every image should have description by using the markdown syntax

```
![Image description](/path/to/image)
```

> **Note:** The size should be 1920 x 1080 to provide seamless user experience.

### Inline Comment
Try to minimize the usage of inline comment. Instead, try to explain what's happening using a normal paragraph. Most of the time, the code area should be used for code when it comes to writing tutorials.

#### Not Preferred
```swift
do { // Let's try to run the function block.
 try autoDriveTesla()
} // the autoDriveTeslas block is only executed within do-try
```

If you need to elaborate on multiple spots, feel free to use numbers instead.

#### Preferred
```swift
do { // 1
 try autoDriveTesla()  // 2
 } catch TeslaError.lostGPS {
  print("Bruh, I'm lost. Hold me tight")  // 3
 } catch TeslaError.lowBattery {
  print("HURRY! 💀")
 }
}
```

When you describe, now you may refer to the spot using the assigned number above. Again, it doesn't mean you can't use in-line comments, but excessive comments should be avoided.

### Writing Tools
  - In-browser markdown editor - [StackEdit](https://stackedit.io/)
  - Example markdown of Intro to Error Handling - [Intro-Error-Handling.md](https://www.dropbox.com/s/tyyr9zuc7nmwbdn/markdown-example.md?dl=0)
  - Spelling and grammar check - [Grammarly](https://www.grammarly.com/)
  - Non-copyrighted images - [Unsplash](https://unsplash.com/)
