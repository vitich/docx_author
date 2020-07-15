# docx_author
Change author in docx

Requirements: python-docx, parallel

Usage: docx_author 'Putin\ Huilo' file.docx

find /home/user/some_dir -type f -name "*\.docx" | parallel docx_author 'Putin\ Huilo'
