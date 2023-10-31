# jsonrpc
## 使用方法
curl -X POST -H "Content-Type: application/json" -d "{\"jsonrpc\": \"2.0\",\"id\": 1,\"method\": \"multiplier\",\"params\":{\"a\":5,\"b\":60}}" "http://localhost:8080/calculator"
