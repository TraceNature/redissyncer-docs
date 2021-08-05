### 任务列表

<img src="https://raw.githubusercontent.com/TraceNature/redissyncer-docs/main/docs/dashboard/img/image-20210805104212484.png" alt="image-20210805104212484" style="zoom: 33%;" />

[comment]: <> (![img]&#40;img/image-20210805104212484.png&#41;)

### 1.查询任务

[comment]: <> (![img]&#40;img/image-20210805104352373.png&#41;)

<img src="https://raw.githubusercontent.com/TraceNature/redissyncer-docs/main/docs/dashboard/img/image-20210805104352373.png" alt="image-20210805104352373" style="zoom:50%;" />

			如图所示，可根据 任务名称、任务ID、任务状态、任务组ID等规则查询相应的同步任务

#### 1.1 根据任务名称查询任务

<img src="https://raw.githubusercontent.com/TraceNature/redissyncer-docs/main/docs/dashboard/img/image-20210805110102545.png" alt="image-20210805110102545" style="zoom:50%;" />

[comment]: <> (![img]&#40;img/image-20210805110102545.png&#41;)

#### 1.2 根据任务ID查询任务

[comment]: <> (![img]&#40;img/image-20210805110133791.png&#41;)

<img src="https://raw.githubusercontent.com/TraceNature/redissyncer-docs/main/docs/dashboard/img/image-20210805110133791.png" alt="image-20210805110133791" style="zoom:50%;" />

#### 1.3根据任务状态查询任务

<img src="https://raw.githubusercontent.com/TraceNature/redissyncer-docs/main/docs/dashboard/img/image-20210805110235565.png" alt="image-20210805110235565" style="zoom:50%;" />

[comment]: <> (![img]&#40;img/image-20210805110235565.png&#41;	)

任务状态共有8种

* creating        任务创建中
* created         任务创建完成
* stop            任务停止
* starting        任务启动中
* finish          任务已完成
* broken          任务异常
* rdbrunning      任务全量数据同步中
* commandrunning  任务增量数据同步中
#### 1.4 根据任务组ID查询任务

[comment]: <> (![img]&#40;img/image-20210805111311181.png&#41;)

<img src="https://raw.githubusercontent.com/TraceNature/redissyncer-docs/main/docs/dashboard/img/image-20210805111311181.png" alt="image-20210805111311181" style="zoom:50%;" />

根据任务组ID可以查询出相同任务组下的所有任务

### 2.创建任务


### 3.停止任务

### 4.删除任务