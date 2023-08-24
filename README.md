# Nature Remo Cloud APIにNode-REDからアクセスするサンプル

## 概要

本リポジトリには、Node-REDからNature Remo Cloud APIを呼び出すフローのサンプルが置いてあります。

## 内容

| ファイル                                                                         | 内容                                                                          |
| :------------------------------------------------------------------------------- | :---------------------------------------------------------------------------- |
| [basic_access_to_nature_cloud_api.json](./basic_access_to_nature_cloud_api.json) | とりあえず家電情報を取得するAPIを呼んでみるフロー                             |
| [subflow_api_request.json](./subflow_api_request.json)                           | node-red-contrib-credentials を使ってAPIのアクセストークンを管理するフロー    |
| [manage_access_token.json](./manage_access_token.json)                           | APIリクエスト処理をサブフロー化し、照明の手動制御を行うフロー                 |
| [retrieve_sensor_data.json](./manage_access_token.json)                          | センサデータを取得し、Remo3の人感センサを用いて照明の自動制御を行うフロー     |
| [control_ac.json](./control_ac.json)                                             | センサデータを取得し、Remo3の温度センサを用いてエアコンの自動制御を行うフロー |


## 関連記事

Nature Engineering Blog内で本リポジトリに公開しているフローの解説を書いています。

* [数年越しのNode-RED入門](https://engineering.nature.global/entry/node-red_cloud-api_1)
* [数年越しのNode-RED入門 (その2)](https://engineering.nature.global/entry/node-red_cloud-api_2)
* [数年越しのNode-RED入門 (その3)](https://engineering.nature.global/entry/node-red_cloud-api_3)

## ライセンス

Unlicenseです。本リポジトリで公開しているフロー本体は特にライセンス表記等気にせず自由に改変して使用していただいて問題ありません。
ただし、本リポジトリの内容物を使用して起きたいかなる損害についても、作者は責任を負いません。自己責任で使用してください。

詳細は [LICENSE](./LICENSE) を参照してください。