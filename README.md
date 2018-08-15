# filebeat-logerm
filebeat module for application log

把module的fields加到 filebeat根目录下的fields.yml，使用global_fields.exe这个程序：
<p>
global_fields.exe -beat_path=E:\gopath\src\github.com\elastic\beats\filebeat -es_beats_path=E:\gopath\src\github.com\elastic\beats -out=fields.yml module
</p>
