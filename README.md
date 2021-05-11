## Try it

    pip3 install mkdocs
    pip3 install pymdown-extensions
    mkdocs serve

## Try with patched mkdocs

Install regular version first

    pip3 install mkdocs
    pip3 install pymdown-extensions

Install the patched version 'somewhere'

    cd /some/path
    git clone https://github.com/dersimn/mkdocs
    cd mkdocs
    pip3 install -e .

Clone this demo repository

    cd /some/other/path
    git clone https://github.com/dersimn/mkdocs-snippets-issue
    cd mkdocs-snippets-issue

Now hotwire the patched version:

    export PYTHONPATH="/some/path/mkdocs"

Build and serve

    mkdocs serve

Browse to <http://localhost:8000>.
