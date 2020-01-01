# Calibre Audio Library Search Page 

This is a simplified web page for searching the https://www.calibre.org.uk/Library.aspx audio book catalogue for RNIB members who have a visual impairment but can use software to browse the internet.

Unfortunately, this was required as calibre confirmed that there is equivalent accessibility page that can be used.

The implementation is based upon a series of Javascript functions which takes the user supplied search terms and submits them to the Calibre search form. If the returned results are paged, this web page will send requests for all pages (up to a max of 20 pages) and aggregate the results onto one single page as a HTML table for easier reading by the sight software.
