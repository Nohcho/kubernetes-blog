docker build -t aakhmiev/posts .

docker push aakhmiev/posts

kubectl apply -f posts-depl.yaml

kubectl rollout restart deployment posts-depl

