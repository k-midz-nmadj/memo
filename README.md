https://mnxp.zendesk.com/hc/ja/articles/4406530045849--NXP-%E3%83%97%E3%83%AD%E3%82%BB%E3%83%83%E3%82%B5%E3%83%BC-%E5%88%9D%E5%BF%83%E8%80%85%E3%82%AC%E3%82%A4%E3%83%89-1-i-MX-%E7%B3%BB%E3%81%AE-Linux-%E3%82%A4%E3%83%A1%E3%83%BC%E3%82%B8%E4%BD%9C%E6%88%90%E6%96%B9%E6%B3%95

https://mnxp.zendesk.com/hc/ja/articles/31943324028057--NXP-%E3%83%97%E3%83%AD%E3%82%BB%E3%83%83%E3%82%B5%E3%83%BC%E5%88%9D%E5%BF%83%E8%80%85%E3%82%AC%E3%82%A4%E3%83%89-8-i-MX-Yocto-Project-Bitbake-%E3%81%AB%E9%96%A2%E3%81%99%E3%82%8B-TIPS

https://packages.debian.org/ja/sid/armhf/libsqlite3-dev/download

https://packages.debian.org/ja/sid/armhf/librabbitmq-dev/download

https://packages.debian.org/ja/sid/armhf/gdbserver/download

dpkg -i *.deb

============================================================================================


1. WSLのインストール(wsl --install)

2. WSLへSDK(gcc,gdb,make...)インストール

3. Windows上にVScodeインストール

4. 拡張機能"Remote Development"(Remote WSL)インストール

5. WSL内のソースディレクトリから"code ."コマンド実行

7. 拡張機能"C/C++ Extension Pack"インストール

8. "tasks.json"にmakeコマンドと、sshコマンド(ターゲットへの実行ファイル転送、gdbserver起動)を追記

9. "launch.json"にデバッガ(gdb)のパス(miDebuggerPath)と、ターゲットアドレス(miDebuggerServerAddress)を追記


https://learn.microsoft.com/ja-jp/windows/wsl/tutorials/wsl-vscode

https://zenn.dev/meiryo7743/articles/set-up-c-lang-env-in-vs-code-and-wsl2

https://zenn.dev/kail/articles/fe7cdd321db9ba

https://qiita.com/_masa_u/items/d3c1fa7898b0783bc3ed

https://qiita.com/Soramame11/items/3a54c0aa45d0869d9395



https://code.visualstudio.com/docs/cpp/launch-json-reference

https://qiita.com/kkrtech/items/3b9cadba78ca3147fe64
