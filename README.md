# CS50W - Project 1 - Wiki
 Wikipedia-like online encyclopedia

**Python files:**
  * _`manage.py`_: main application to run server 
  * **wiki:**
     _`asgi.py`_ _`settings.py`_ _`urls.py`_ _`wsgi.py`_

   * **encyclopedia:**
      _`admin.py`_ _`apps.py`_ _`modles.py`_ _`tests.py`_ _`urls.py`_ _`util.py`_ _`views.py`_
    
**HTML files:** (located in: _encyclopedia/templates/encyclopedia_)
  * _`layout.html`_
    - Basic layout for rest of pages extend
  * _`index.html`_
    - Main page with list of all entries 
  * _`entry.html`_
    - Content for an entry
  * _`search.html`_
    - Shows entries for a search query
  * _`create.html`_
    - Shows forms to create a new entry/page
  * _`edit.html`_
    - Shows forms to edit a entry/page
  * _`error.html`_
    - Displays error for page that doesn't exist
    
**CSS file:** (located in: _encyclopedia/static/encyclopedia_)
  * _`style.css`_
     
      
### Overview:
Wikipedia like website that consists of entries on various topics. All entries are listed at the homepage (_index.html_). Clicking on an entry will bring you to the entry page, with the url of the ENTRY as: `/wiki/ENTRY`. Going to a page that does not exist will bring the user to an error page saying that the webpage does not exist (_error.html_). A user can create a new page for an entry that is not in the list of entries `/create` (_create.html_), or they can also edit an existing entry `/wiki/ENTRY/edit` (_edit.html_). Users can use markdown to style their entries. A user can search through the list of entries by using the text box in the side pannel `/search/` (_search.html_). 
