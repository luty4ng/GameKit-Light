# Lightweight version of GameKit

### Last Update

2022/07/31

### Core

- Base
  - 单例 ``SingletonBase``
  - Mono单例  `` MonoSingletonBase``
  - 命令 ``Command``
  - UI组件 ``UIForm`` ``UIGroup``

- Data Structure
  - 树和节点 ``Tree``
  - 缓存链表 ``CachedLinkedList``
  - 限度链表 ``LinkedListRange``
  - 多值字典 ``MultiDictionary``
  - 缓存字典 ``QueueDictionary``
  - 环形缓冲 ``RingBuffer``
  - 序列化链表和序列化字典 ``Serialization``
  - 类名对主键 ``TypeNamePair``

- GameKit
  - GameKit相关基础设计

- Helper（辅助器相关）
- Manager （用于快速访问的单例管理器）
  - ``AudioManager`` 音效管理器
  - ``EventManager`` 基于泛型的事件中转
  - ``InputManager`` 输入管理器，基于``Input``重封装
  - ``PoolManager`` 面向``GameObject``的快速缓冲池
  - ``ResourceManager`` 基于``Resource``和``Addressable``的快速资源管理器
  - ``ScenesManager`` 场景管理器，基于``SceneManagement`` 重封装
  - ``SerializeManager`` 快速序列化器，支持``Json``和二进制
  - ``UIManager`` 注册时的UI管理器

- Prefab （放置于Launcher中的Kit核心预制体，模仿GF）

