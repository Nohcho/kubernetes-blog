docker build -t aakhmiev/posts:0.0.2 .

kubectl apply -f posts-depl.yaml

kubectl rollout restart deployment posts-depl

