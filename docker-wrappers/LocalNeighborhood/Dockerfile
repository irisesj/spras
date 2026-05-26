# Create a Docker image for the Local Neighborhood algorithm here
docker run -w /data --mount type=bind,source=/${PWD},target=/data \
  irisj02/local-neighborhood python local_neighborhood_alg.py \
  --network /data/ln-network.txt --nodes /data/ln-nodes.txt \
  --output /data/ln-output.txt
