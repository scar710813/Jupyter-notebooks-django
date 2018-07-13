# 0.5 - 13th July 2018

- Adjust dependency of Wagtail to < 2.3
- Fix support of Wagtail 2 #46 - @johnfraney
- Fix example in the README #42 - @benjaoming
- Change TODO #42 - @benjaoming

# 0.5a3 - 26th March 2018

- Whitelist `<hr>` and `<br>` tags #33 - @tm-kn
- Fix compatibility for markdown panel in Wagtail 2.0 #37 - @rspeed

# 0.5a2 - 14th February 2018

- Update simplemde to 1.11.2 #31 - @stuaxo
- Update imports to work with Wagtail 2.0 #31 - @stuaxo
- Fix packaging issues so static files are included in PyPI

# 0.5a1 - 7th December 2017

- Fix problem with app loading
- Make it compatible with newer versions of Wagtail that require `context` parameters in blocks' `render_basic` method.
- Restructure app, refactor code. Add depreciation warnings.
