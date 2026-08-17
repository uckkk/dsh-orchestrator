# dsh-orchestrator

DSH 多机协同上架协调仓库。

- board/queue.json：待办 / 已发布 / 被占用
- board/claims/*.json：各机器的认领（乐观锁）n- board/status.json：面板聚合快照
