# README


# PARA HABILITAR O i3 EXECUTE:
sudo tee /usr/share/xsessions/i3.desktop << 'EOF'
[Desktop Entry]
Name=i3
Comment=improved dynamic window manager
Exec=i3
TryExec=i3
DesktopNames=i3
Type=Application
EOF

---

Para verificar quais arquivos de sessão estão disponíveis no sistema para o gerenciador de login, liste o conteúdo do diretório de sessões do Xorg com o comando:

Bash
ls -la /usr/share/xsessions/

---

# PARA COEMCAR A USA-LO
1. ENCERRE A SESSAO E FAÇA LOGIN PELO i3 no lightDM ,(obs: tEM QUE TER LOGIN NO SISTEMA)
2.PARA_STARTAR: `startx`
3. Abrir terminal ocm o i3: mod+enter

