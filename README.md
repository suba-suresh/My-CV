# autoCV

A clean CV template in LaTeX along with a GitHub action that complies the `*.tex` file and publishes a new PDF version when new changes are pushed to the repo

## Template Design

The template is designed to be clean with sections for
- Tabular sections for Work Experience, Education and Projects
- Header with Font Awesome icons

## Quickstart
- Fork this repo (you can use the `Use this template` button)
- Modify the `cv.tex` file and push changes to your repo
- The complied PDF will be available under the `build` branch

You can get a direct link to the generated PDF which you can use on your website, LinkedIn etc. that will always point to the latest version of your CV. Once your site is published, your CV will be accessible at: `https://username.github.io/repo-name/`

For this, after editing your copy of `cv.tex` and pushing changes to your repo, under Settings -> Pages set your Github Pages source to the `build` directory

![](https://i.imgur.com/lwATw1o.png)

## This template on Overleaf

<a href="https://www.overleaf.com/latex/templates/autocv/scfvqfpxncwb"><img alt="Overleaf" src="https://img.shields.io/badge/Overleaf-47A141.svg?style=for-the-badge&logo=Overleaf&logoColor=white"/></a>

Also, if you have a premium subscription to Overleaf, you can use Overleaf's GitHub integration to push changes to your GitHub repo directly from Overleaf.

## Compiling the CV on your local computer
- type `make` in the `autoCV` directory to produce file `cv.pdf`
- you can optionally type `make clean` or `make distclean` to remove intermediate files


## Acknowledgments

I would like to express my gratitude to <a href="https://github.com/jitinnair1">Jitin</a>  for creating the original template that served as the foundation for this project. Thank you for generously sharing your work with the community and for granting permission to adapt and modify it according to my needs.

## Detailed Instructions..
[.. are available here](https://github.com/jitinnair1/autoCV/wiki/How-to-use-autoCV:-Detailed-Instructions)





