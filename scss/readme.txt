■Sassファイルディレクトリ構成
smacssルールに基づいたディレクトリ構成になっています。

・style.scss
メインのcssです。
style.cssとして出力されます。

・_core.scss
各ファイルで使うscssを読み込むためのファイルです。
特に編集する必要はありません。

・_general.scss
汎用クラスを記述するファイルです。

・baseディレクトリ
ベースのcssです。
特に編集する必要はありません。

・coreディレクトリ
各ファイルで使うscssをまとめたディレクトリです。
変数は_variable.scssに記述するようにしてください。
font-sizeなどは必ずこの変数を使うようにしてください。
基本的なmixin、extend、functionもこのディレクトリに集約します。

・layoutディレクトリ
layoutに関わるファイルです。
class名の先頭に「.l-」を付けるようにしてください。

・moduleディレクトリ
moduleに関わるファイルです。

・stateディレクトリ
stateに関わるファイルです。
class名の先頭に「.is-」を付けるようにしてください。
