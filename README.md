## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/sandeepv-1996/The_Unix_Workbench_Johns_Hopkins_University/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)

```
#!/usr/bin/env bash

function guess(){
    true_ans=$(ls -l |grep "^-"|wc -l)
    while true;
    do
        echo "pleas enter your guess"
        read  number
        if [ $number -lt $true_ans ]
        then
            echo "your guess is Less then the true number"
        elif [ $number -gt $true_ans ]
        then
            echo "your guess is Greater then the true number"
        else
            echo " congratulation,you are right!"
        break;
        fi
    done
}
echo "guess the files number in the current directory!"
guess

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/sandeepv-1996/The_Unix_Workbench_Johns_Hopkins_University/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
