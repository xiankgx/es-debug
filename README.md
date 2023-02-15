# es-debug

## Usage
```
# Download dataset.json file
wget https://gx-stuffs.s3.amazonaws.com/shared/es-debug/dataset.json

# Start Elasticsearch single-node cluster with Docker Compose
docker-compose up -d

# Run jupyter notebook
jupyter notebook --ip 0.0.0.0

# Then run notebook 'debug_hybrid_search.ipynb'
```
