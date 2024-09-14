<docs-decorative-header title="パフォーマンス" imgSrc="adev/src/assets/images/overview.svg"> <!-- markdownlint-disable-line -->
アプリケーションのパフォーマンスを最適化するためのさまざまな方法について学びましょう。
</docs-decorative-header>

開発者の最優先事項の1つは、アプリケーションのパフォーマンスを可能な限り向上させることです。これらのガイドは、パフォーマンスの高いアプリケーションを構築するためのベストプラクティスに従うのに役立ちます。

とはいえ、これらのベストプラクティスは、アプリケーションのパフォーマンスをある程度までしか向上させられません。最終的には、パフォーマンスを測定して、アプリケーションに最適なカスタム最適化を理解することをお勧めします。

| ガイドの種類                              | 説明                                                                                                |
| :---------------------------------------- | :--------------------------------------------------------------------------------------------------------- |
| [遅延可能なビュー](/guide/defer)                | `@defer`ブロックで対応する部分をラップすることで、テンプレート内の選択された依存関係の読み込みを遅らせます。                                                    |
| [画像の最適化](/guide/image-optimization) | `NgOptimizedImage`ディレクティブを使用して、画像の読み込みのベストプラクティスを採用します。                            |
| [サーバーサイドレンダリング](/guide/ssr)             | ロード時間を短縮するために、サーバーでページをレンダリングする方法について学びます。                                 |
| [ビルド時の事前レンダリング](/guide/prerendering)  | 静的サイドジェネレーション(SSG)とも呼ばれ、ロード時間を短縮するための別のレンダリング方法です。           |
| [ハイドレーション](/guide/hydration)                   | サーバーサイドレンダリング後にアプリケーションの状態を復元し、可能な限り既存のDOM構造を再利用することで、アプリケーションのパフォーマンスを向上させるプロセスです。 |