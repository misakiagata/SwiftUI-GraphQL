# SwiftUI-GraphQL
This is a sample project of [SwiftUI](https://developer.apple.com/xcode/swiftui/) and [GraphQL](https://www.apollographql.com/docs/)(apollo-ios) using [GitHub GraphQL API](https://docs.github.com/ja/graphql)

<img src=https://user-images.githubusercontent.com/40904974/118585646-50b63400-b7d4-11eb-90ae-341dcc4f1476.png width=280>

## 🛠 Run
To try this sample project, you need to set `Github Personal Access Token` below.

SwiftUI-GraphQL/Sources/GraphQL/Intercepter/AuthIntercepter.swift

```
/// TODO: GithubのPersonal Access Tokenを追加
request.addHeader(name: "Authorization", value: "Bearer {TOKEN}")
```
