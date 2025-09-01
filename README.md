# My own CV template in Typst based on [typst-chi-cv-template](https://github.com/matchy233/typst-chi-cv-template)

This is my first time trying to change a template in Typst and this helped me in getting familiar with `typst` functionalities. And I think errors or some shortages are inevitable so PRs and questions are of course welcomed :)

## New content and what's the existing problem
Since I am a high school student, I create some new functions so that a few contents in a (high-school-student) CV may fit it better.
- A `#grade` function for education experiences with _italic_ GPA.
- An `#honor` function for single honor. `tl` for the name of honor, `tc` for the institution, `tr` for time, and `content` for an explanation of some unfamiliar awards.
- A `#multihonor` function used together with `#honorline`. Add `#honorline` functions in the `#multihonor()` and connect each other using `+`. As original `#honor` function,  `[]` is for explanation.
- A `#multicventry` function used together with `#positionline`.

PS: An svg file for AoPS small logo `AoPS_small_logo.svg` is created for AoPSers.

## Usage
### Using Typst web app

Upload `chicv.typ`, `fontawesome.typ`, `resume.typ`, `AoPS_small_logo.svg` (if u also want to show your AoPS account at the beginning of CV) and `fonts/FontAwesome6.otf` to [Typst](https://typst.app/), and then you can edit the CV, or clone this repo to local and use typst to compile locally 

## Sample Output

![Sample output](CV-sample-preview.jpg)
[PDF file](CV_sample.pdf)
