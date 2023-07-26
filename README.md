# dt-http

Example of data transfer server using HTTP.

## Upload
`curl -i -X POST -F "file=@up-file.txt;filename=file.txt" localhost:5000/upload`

## Download
`curl -X GET -o down-file.txt localhost:5000/download/file.txt`
