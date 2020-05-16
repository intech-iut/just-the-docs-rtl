<p align="right">
    <a href="https://badge.fury.io/rb/just-the-docs"><img src="https://badge.fury.io/rb/just-the-docs.svg" alt="Gem version"></a> <a href="https://github.com/pmarsceill/just-the-docs/actions?query=workflow%3A%22Master+branch+CI%22"><img src="https://github.com/pmarsceill/just-the-docs/workflows/Master%20branch%20CI/badge.svg" alt="Build status"></a>
</p>
<br><br>
<p align="center">
    <h1 align="center">Just the Docs for Right-to-Left Scripts</h1>
    <p align="center">A modern, highly customizable, and responsive Jekyll theme for documentation with built-in search.<br>Easily hosted on GitHub Pages with few dependencies.</p>
    <p align="center"><strong><a href="https://pmarsceill.github.io/just-the-docs/">See the original one</a></strong> and <strong><a href="https://kurdishxelatex.github.io/Sorani">the forked one with right-to-left support</a></strong> in practice</p>
    <br><br><br>
</p>

![jtd](https://user-images.githubusercontent.com/896475/47384541-89053c80-d6d5-11e8-98dc-dba16e192de9.gif)

# Additional features

You can find out more about this awesome template in the [original repository](https://github.com/pmarsceill/just-the-docs). Here, I would like to highlight the two important features which are added to the original template for making the current one:

- Supporting languages using right-to-left scripts like Arabic, Hebrew, Sorani Kurdish and Persian. For this purpose, [https://github.com/DediData/Bootstrap-RTL](Bootstrap-RTL) is used.
- In the original template, the logo should be quite small. In this one, you can put your logo right above the items in the navigation bar giving you a bigger space. The name of the logo file can be modified at `/_includes/nav.html`. If you would like to change it, do so at `_sass/base.scss`.

## Usage

[View the documentation](https://pmarsceill.github.io/just-the-docs/) for usage information.

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is set up just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When the theme is released, only the files in `_layouts`, `_includes`, and `_sass` tracked with Git will be released.

## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
