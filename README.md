# Swift Programming for macOS

:apple: :computer:

There are plenty of books, videos, and online resources for developing iOS apps. Despite the fact that iPhone and iPad apps require a Mac for code development, there is very little information about actually creating native Mac applications. The examples in this repository demonstrate various aspects of Mac app development using the latest versions of Swift and SwiftUI. Hopefully these examples will provide a useful resource for Mac developers.

## Website

See https://gavinw.me/swift-macos for the website which discusses the examples in this repository.

The website is built with [Jekyll](https://jekyllrb.com) and hosted with [GitHub Pages](https://pages.github.com). Files for the website are in the `docs/` folder. Since this is a project website (not a user or organization website) the baseurl must be set to the repository name `baseurl: /swift-macos` in the `docs/_config.yml` file. Therefore, paths in the HTML and Markdown files must start with `/swift-macos`.

Run the Jekyll server with the following command:

```bash
$ bundle exec jekyll serve
```

Commands to update the Ruby Bundler gem and the GitHub pages gem:

```bash
$ gem update bundler
$ bundle update github-pages
```

## Contributing

Submit a Pull Request if you would like to contribute to this project. Questions and other comments can be submitted on the Issues page.

## Support

Support this project by using the **:heart: Sponsor** button at the top of this page. Thank you :smile:.

## License

Code in this repository is available under the MIT License - see the [LICENSE](LICENSE) file for more information.
