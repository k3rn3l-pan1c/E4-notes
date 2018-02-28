A collection of useful notes and pdfs for the [Electronics IV course](http://http://www.ua.pt/deti/uc/2367) at [Aveiro University](https://www.ua.pt/).

A website is also available [here](https://k3rn3l-pan1c.github.io/E4-notes/).

## Published Notes
_[WIP]_

## Note taking process
 1. Notes are taken using pandoc markdown extended syntax
	- Check [Adam cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) or [Wikipedia](https://en.wikipedia.org/wiki/Markdown) for more information and useful tips
2. Using [pandoc](https://pandoc.org/), the notes are converted into a eye-candy pdf, using tex as an intermediary file type
	- The latex compiler used is xelatex
	- The [Eisvogel](https://github.com/Wandmalfarbe/pandoc-latex-template) template is used with small modifications
3. Using an yaml header, some metadata and rendering options are provided
4. Some of the used diagrams are generated using either [dot](https://en.wikipedia.org/wiki/DOT_(graph_description_language)) or [tikz](https://ctan.org/pkg/tikz-page). The remaining were copied from the course slides.

### DOT & Grphviz
The [dot graph description language](https://en.wikipedia.org/wiki/DOT_(graph_description_language)) is a graphic description language, enable the fast creation of reasonably neat diagrams

For interpreting the dot code, [graphviz](https://graphviz.gitlab.io/) as used.

For more information on dot and graphviz, check out [this amazing guide](https://www.google.pt/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0ahUKEwjUrryp4srYAhWBtxQKHWKzA68QFggzMAA&url=https%3A%2F%2Fgraphviz.gitlab.io%2F_pages%2Fpdf%2Fdotguide.pdf&usg=AOvVaw1NgHmOrdTb4E59oQvAx-jW)

### Tikz
The Latex vector graphic language, [Tikz](https://en.wikibooks.org/wiki/LaTeX/PGF/TikZ), that uses geometric/algebric description to create beatiful diagrams

For more information, check out [this amazing guide](https://www.google.pt/url?sa=t&rct=j&q=&esrc=s&source=web&cd=6&cad=rja&uact=8&ved=0ahUKEwic-vO3msnZAhWS6lMKHY6sD1EQFgh8MAU&url=https%3A%2F%2Fcremeronline.com%2FLaTeX%2Fminimaltikz.pdf&usg=AOvVaw0hupwalyz2Z7QtRtaqYbR0)


## Publishing
To ease the publish of an eye-candy pdf:
```bash
 # Assuming that exists a metadata file named notes.yaml in the metadata folder
./renderpdf <notes.md>

# Assuming a metadata file is going to be provided
./renderpdf <notes.md> <metadata_file.yaml>

```
## Disclaimer
Currently this work is **highly experimental and not yet scientific reviewed**.
**Do not trust this notes by themselves**. They are meant to complete other materials, **not replace them**.

## Acknowledgement
This work is a direct product of the lectures notes toked during Electronics IV classes in the academic year of 2017/18, lectured by Prof. Pedro Fonseca. 

This raw notes were later improved and filtered using as scientific reference the lecture slides from Prof. Pedro Fonseca.

## Roadmap
 
- [ ] Curate Raw notes
- [X] Improve the publishing scripts
- [ ] Improve the publish template
- [ ] Provide a static website with all the notes


## License
The content of this project itself is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/) and the underlying source code is under the [MIT license](https://opensource.org/licenses/mit-license.php).
