
<div align="center">
    <img src="https://jqhph.github.io/dcat-admin/assets/img/logo-text.png" height="80"> 
</div>
<br>
<p align="center"><code>Dcat Admin</code> is based on <a href="https://www.laravel-admin.org/" target="_blank">laravel-admin</a>. It allows you  to quickly build a fully functional backend system of high value with very little code. Built with a wealth of common back-end components, out of the box, allowing developers to say goodbye to redundant HTML code, very back-end developer-friendly.</p>

<p align="center">
<a href="https://learnku.com/docs/dcat-admin/1.x">learnku文档</a> |
<a href="http://www.dcatadmin.com/">Homepage</a> |
<a href="https://jqhph.github.io/dcat-admin/demo.html">Demo</a> |
<a href="https://github.com/jqhph/dcat-admin-demo">Demo Source Code</a> |
<a href="#extensions">Extensions</a>
</p>

Dcat Admin Docs


## local docs 

```bash

docker build . --tag ghcr.io/yingchaoorg/local_docs-dcat-admin:master
# 临时运行 (停止后删除)
docker run -p  34803:80 --name  local-docs-dcat-admin-dev --rm ghcr.io/yingchaoorg/local_docs-dcat-admin:master
# 后台运行
docker run -p  34803:80 --name local-docs-dcat-admin-dev -d ghcr.io/yingchaoorg/local_docs-dcat-admin:master

docker stop local-docs-dcat-admin-dev


```
