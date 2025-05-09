# C3MA Dudle Docker

Based on <https://github.com/jpkorva/dudle-docker>

```bash
git clone https://github.com/jpkorva/dudle-docker.git dudle-docker
cd dudle-docker
git clone https://github.com/kellerben/dudle.git cgi
tar -xzf dudle.tar.gz -C dudle_data
docker compose up -d
```

Now reachable at <http://host:8080>