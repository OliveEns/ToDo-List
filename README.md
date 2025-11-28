# 待办事项清单 (Todo List)

一个简单的待办事项管理应用，帮助你高效管理任务、追踪进度并通过积分奖励系统保持动力。

## 功能特点

- **任务管理**：支持添加、完成、删除任务，以及创建子任务，实现多级任务管理
- **积分系统**：为每个任务设置完成积分，完成后获得相应积分奖励
- **奖励兑换**：可自定义奖励清单，使用积累的积分兑换奖励
- **数据持久化**：使用本地存储保存所有数据，刷新页面不丢失
- **数据导入导出**：支持数据备份与恢复，确保数据安全
- **任务统计**：通过GitHub风格的贡献日历展示每日完成任务数量，直观了解你的任务足迹
- **筛选功能**：可按全部、未完成、已完成筛选任务


## 界面预览

<div style="position: relative; width: 100%; height: 500px; overflow: hidden;">
<iframe style="position: absolute; width: 1200px; height: 800px; transform: scale(0.6); transform-origin: top left; border: 1px solid #ddd;" src="https://oliveens.github.io/ToDoList" frameborder="1" scrolling="yes" sandbox="allow-scripts allow-same-origin"></iframe>
</div>

## 使用方法

1. **添加任务**：在顶部输入框中输入任务内容，设置完成积分，点击"添加任务"按钮
2. **管理任务**：
   - 点击复选框标记任务为已完成/未完成
   - 点击"删除"按钮移除任务
   - 点击"添加子任务"为任务创建子任务
3. **积分与奖励**：
   - 完成任务获得积分
   - 点击"奖励兑换"查看并兑换奖励
   - 可添加自定义奖励
4. **数据管理**：
   - 点击"导出数据"保存数据到本地
   - 点击"导入数据"恢复之前保存的数据
   - 可通过"全局重置"清空所有数据
5. **任务统计**：底部的贡献日历展示每日任务完成情况，点击年份可切换查看

## 网址

[待办事项清单|Todo List](https://oliveens.github.io/ToDoList)

## 技术栈

- HTML5
- CSS
- JavaScript