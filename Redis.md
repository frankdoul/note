
过期策略有哪些？
淘汰策略有哪些？
oeviction：当内存使用达到阈值的时候，所有引起申请内存的命令会报错。

· allkeys-lru：在主键空间中，优先移除最近未使用的key。

· volatile-lru：在设置了过期时间的键空间中，优先移除最近未使用的key。

· allkeys-random：在主键空间中，随机移除某个key。

· volatile-random：在设置了过期时间的键空间中，随机移除某个key。

· volatile-ttl：在设置了过期时间的键空间中，具有更早过期时间的key优先移除。
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTM2MDcwMTY1XX0=
-->