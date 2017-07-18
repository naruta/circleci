# circleci

CircleCI用のイメージです。秘密情報などは入れないでください。

masterへのコミットやタグ打ちを行うと自動でビルドされたイメージがDocker Hub上にアップロードされます。

https://hub.docker.com/r/cybozubee/circleci/

タグ名は、 ```<Javaバージョン>-<nodeバージョン>-<1から始まる連番>``` で付けます。例えば、Java8でnode.jsが6.11.1のイメージの最初は ```8-6.11.1-1``` となり、Javaのバージョンもnode.jsのバージョンも変わらない修正をした場合は ```8-6.11.1-2``` となります。
