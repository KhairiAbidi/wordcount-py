## Simple Wordcount with hadoop streaming
```
  hadoop jar $HADOOP_HOME/share/hadoop/tools/lib/hadoop-streaming-3.2.0.jar \
  -input input -output output \
  -mapper WordCountMapper.py \
  -reducer WordCountReducer.py
```
