# cigp
## 容器監控工具(cAdvisor監控收集+Prometheus存儲數據+Grafana展示圖表+Prometheus)


### 使用說明
docker-compose.yml
如果cadvisor使用google/cadvisor的image無法建立container
可以先查看log
```
docker logs -f [container-id]
```
如果出現錯誤
```
F0407 02:12:19.453424       1 cadvisor.go:146] Failed to create a Container Manager: mountpoint for cpu not found
```
可以換image來源,換成 gcr.io/cadvisor/cadvisor試試


