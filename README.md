# passpath
PASSパス - パス(Path)をPass(渡す)するだけのソフト  
フォルダのPathを調べたいときに使えます。  
6年前にリリースしたものを整えてossにしました。  
あの頃は知識が少なく、こんな簡単なものばかり作っていました。  
仕組みはものすごく簡単なものです。  
このソフトは以下の4行しか重要なコードがないので、何かソフトを作りたいな って考えている方は参考にしてみてくださいね!  
``` Form1.cs
            if (folderBrowserDialog1.ShowDialog() == DialogResult.OK)
            {
                this.textBox1.Text = folderBrowserDialog1.SelectedPath;
                MessageBox.Show("結果を表示しました");
            }
```

