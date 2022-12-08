# ChatGPT 提问工程师开发指南

<img src="https://img.shields.io/badge/-ChatGPT%20%E6%8F%90%E9%97%AE%E5%B7%A5%E7%A8%8B%E5%B8%88-%23198A7A">

## ✨ 关于本指南

由于 `🤖️ChatGPT` 的回答是开放性和发散的，但对于具体的开发任务，更多是需要针对性的回答。为了提高 `ChatGPT提问工程师` 在与 `🤖️ChatGPT` 合作编程中的效率，而创建了这份文档来收集和整理常用的`命令`「这个所谓的`命令`其实也就是自然语言了」。

该指南旨在帮助 `ChatGPT提问工程师` 提高提问效率，欢迎 PR 👏👏👏 补充更多好问法。

_注意：本文档仅针对 `ChatGPT提问工程师` 开发工作的场景。使用 `🤖️ChatGPT` 应该是开放性的，与 `🤖️ChatGPT` 进行无限可能的思维碰撞才能给人类带来颠覆性的应用 🌟。_

## 📃 文档使用说明

-   命令稳定性：强 中 弱

    -   由于 `🤖️ChatGPT` 的回答是发散的，命令稳定性代表符合期望的程度。
    -   尝试 10 次
        -   强 `> 8次符合期望`
        -   中 `> 5次符合期望`
        -   弱 `> 2次符合期望`

-   传参数的方式

    -   命令通过换行加参数即可
    -   例子 1 ：`优化代码` 命令的用法（假设代码是参数）

        ```
        优化代码

        const hello = "🤖️ChatGPT";
        ```

-   编程语言类型
    -   什么都支持

## 📃 命令列表

### 对话环境设置

---

-   **切换人类语言**

    ```
    接下来的对话都用{中文/英文}回答我
    ```

    -   命令稳定性：强
    -   默认值：你用啥语言问，他用啥语言回答。偶尔抽风会一直用英文回答，这时可以用此命令调整。
    -   例子
        ```
        接下来的对话都用中文回答我
        ```

### 通用

---

-   **继续完成回答**

    ```
    继续
    ```

    -   命令稳定性：强
    -   用途：`🤖️ChatGPT` 回答太长的内容时经常会中断，可用该命令要求完成回答

### 需求分析

---

TODO

### 设计

---

-   **优化文案**

    ```
    优化文案
    ```

    -   命令稳定性：强

-   **细化方案**

    ```
    细化方案
    ```

    -   命令稳定性：强

-   **生成 UML**

    ```
    用 - | . ^ > < 这类符号绘制 UML
    ```

    -   命令稳定性：中
    -   用途： 由于 `🤖️ChatGPT` 不能输出图片，可以通过这个方式来展示，
    -   备注： 效果不太好，经常歪歪扭扭的
    -   例子：

        ```
        用 - | . ^ > < 这类符号绘制 UML

        interface AComponent {
                id: string;
                name: string;
                bComponent: BComponent;
        }
        interface BComponent {
                id: string;
                name: string;
        }
        ```

### 编码

---

-   **评审代码**

    ```
    评审代码
    ```

    -   命令稳定性：强

-   **检查代码出错原因**

    ```
    检查代码出错原因
    ```

    -   命令稳定性：强

-   **重构/优化代码**

    ```
    重构代码
    ```

    -   命令稳定性：强

-   **生成接口文档**

    ```
    生成 markdown 格式文档
    ```

    -   命令稳定性：中
    -   备注：由于每次生成都不一样，其实不太好在开发迭代中维护，希望能摸索出更好的方式

### 测试

---

-   **添加单元测试**

    ```
    添加单元测试
    ```

    -   命令稳定性：强

-   **生成 Mock 数据**

    ```
    生成一份 json 格式数据
    ```

    -   命令稳定性：中
    -   例子：

        ```
        生成一份 json 格式数据

        interface AComponent {
                id: string;
                name: string;
                bComponent: BComponent;
        }
        interface BComponent {
                id: string;
                name: string;
        }
        ```

## 📚 `ChatGPT提问工程师` 书籍推荐

[《学会提问》](https://book.douban.com/subject/35513147/)

## 📚 其他相关文档

[OpenAI 推出超神 ChatGPT 注册攻略来了
](https://www.v2ex.com/t/900126?p=2)
