
✅ k get pod -o wide
  👉 minikube ssh -- curl -I 10.244.1.248:8080


✅ 로컬 브라우저로 바로 보고 싶으면(둘 중 택1, deploy 사용중일때는 2안으로 테스트)
 
 [service 사용할때 .... 지금은 사용지 않음으로 port-ward 로 사용]
 👉 minikube service  lsy-node-app --url
 or
  👉 kubectl port-forward deploy/lsy-node-app 8088:8080 
  👉 http://localhost:8088

 ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
 
