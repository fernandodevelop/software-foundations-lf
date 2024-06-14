FROM coqorg/coq:8.18.0
RUN opam install vscoq-language-server -y
COPY git-bash-aliases.sh /home/coq/git-bash-aliases.sh
RUN echo "source ~/git-bash-aliases.sh" >> /home/coq/.bashrc
