# Atom text snippets for Hugo

Snippets for [Hugo's Go templates](https://gohugo.io/templates/introduction/).

Heavily inspired by [regisphilibert/Hugo-Snippets (Hugo Snippets for Sublime Text 3!)](https://github.com/regisphilibert/Hugo-Snippets)

## Installation

* Either copy the content of `snippets/hugo-snippets.cson` and paste it into your Atom snippets file (See [the Atom flight manual](https://flight-manual.atom.io/using-atom/sections/snippets/#creating-your-own-snippets) for further information).
* Or clone this repository, `cd` into it and link it to your local Atom packages folder with `apm link`.

## Usage

Use "HTML (Go)" as a language type.

## Available snippets

| Snippet      | Tab trigger | Output                             |
| :----------- | :---------- | :--------------------------------- |
| Curlies      | **x**       | `{{ }}`                            |
| Dot          | **dot**     | `{{ . }}`                          |
| If           | **if**      | `{{ if }} {{ end }}`               |
| If/Else      | **ife**     | `{{ if }} {{ else }} {{ end }}`    |
| If/Else if   | **ifei**    | `{{ if }} {{ else if }} {{ end }}` |
| With         | **with**    | `{{ with }} {{ end }}`             |
| With/Else    | **withe**   | `{{ with }} {{ else }} {{ end }}`  |
| Range        | **range**   | `{{ range }} {{ end }}`            |
| Partial      | **partial** | `{{ partial "" . }}`               |
| Block        | **block**   | `{{ block "main" . }} {{ end }}`   |
| Block define | **define**  | `{{ define "block" }} {{ end }}`   |
| Comment      | **comment** | `{{/* */}}`                        |
| Variable     | **var**     | `{{ $var := what }}`               |
| Debug        | **debug**   | `{{ printf "%#v" }}`               |
