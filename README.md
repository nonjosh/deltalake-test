# deltalake-test

## Setup

start docker container

```sh
docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "${PWD}":/home/jovyan/work jupyter/pyspark-notebook
```

## References

- [https://jupyter-docker-stacks.readthedocs.io/en/latest/using/specifics.html]
- [https://levelup.gitconnected.com/using-docker-and-pyspark-134cd4cab867]
- [https://www.datamechanics.co/blog-post/spark-and-docker-your-spark-development-cycle-just-got-ten-times-faster]
- [https://medium.com/@suci/running-pyspark-on-jupyter-notebook-with-docker-602b18ac4494]
- [https://spark.apache.org/docs/latest/running-on-kubernetes.html]
