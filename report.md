# Agentic Workflow 与多智能体 + 进阶实验B 报告
## 一、生产级 Agentic Workflow 内容（思维导图）
```mermaid
mindmap
  root((生产级 Agentic Workflow))
    案例
      Claygent：网络扫描、潜客研究
      ServiceNow AI Agents：工单触发 → 知识库RAG → 生成处理建议，人类保留决策权
    核心术语
      工作流编排
      子工作流
      多智能体
      批处理节点
      选择器
    电商客服多智能体协作案例
      场景：主管Agent派单；订单、促销、人工三类专业Agent分工；复杂业务拆分，不依赖单一万能体
      编排：批处理节点并行批量生成商品文案；选择器路由（能答 / 转人工）
      映射：多智能体等价现实科室协作；能力从写提示词升级为搭建智能体组织
