# ReferencesFormatter
Alphabetically sorts and applies hanging indent styling to APA citations list. Features include:

- Applies tag `<p style="text-align: left;" class="hanging-indent">` to each entry
- Can handle lists where some or all of the `<p>` tags described above have already been applied
- Copy/paste list html or upload .txt containing list markup

If you are not using Pressbooks, the hanging indent effect can be achieved by adding the following CSS rule:

```
  .hanging-indent {
  padding-left: 1em;
  text-indent: -1em;
  }
```

Visit the [active GitHub Page](https://fanshaweoerdesign.github.io/ReferencesFormatter/) to use online or download and run locally in your browser -- no server required!
