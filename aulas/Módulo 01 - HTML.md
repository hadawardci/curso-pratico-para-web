# Módulo 01 - HTML

## Introdução

Siga as instruções abaixo para aprender como realizar ações fundamentais e cotidianas no HTML.
as informações em _italic_ representam tags em HTML que voce deve usar, geralmente vc deve utilizar com abertura e encerramento

- Exemplo de tag padrão: <tag-abre-fecha>informação da tag</tag-abre-fecha>.
  Lembre-se sempre que abrir ela deve fechar.
  Essa é uma regra geral, algumas delas são: html, head, body, h1, h5, table, div etc.

```
<p>este é um paragrafo </ p>
```

- Exemplo de tag singular: <tag-independente atributo-opcional="minha-fonte" />.
  Algumas tags devem se encerrar nelas mesma como no exemplo acima.
  Trade isso como exceção, as principais são:
  Imagem

```
<img src="link-aqui" />
```

Tipo de documento

```
<!DOCTYPE html>
```

Quebra de linha

```
<br>
```

Lembre se sempre que ver uma _informação-italica_ você deve entender que trata-se da tag que você deve utilizar no exeplos acima.

Lembre-se sempre de criar o conteúdo com o número da aula.

**Dica:** Ao fim de cada aula, pratique alternando formas de uso o que você aprendeu, evite fazer todas aulas no mesmo dia, ao invés disso use a criatividade para aplicar o conhecimento da aula e juntando com as anterioes para fixar na mente.

---

## Aula 01 - Introdução a HTML

### Crie uma pagina HTML

No mínimo, sempre crie o arquivo HTML com o seguinte conteúdo.

```
<!DOCTYPE html>
<html>
<head>
</ head>
< body>
</ body>
</ html>
```

Faça isso também nas próximas aulas.

#### _head_

- Insira o _title_ da pagina

```
Módulo 01 - HTML | Aula 01 - Introdução a HTML
```

#### _body_

- Adicione o seguinte título _h1_

```
Introdução a HTML
```

- Adicione o seguinte subtitulo com _h2_

```
Primeiros passos na WEB
```

- Adicione um parágrafo _p_

```
Estamos iniciando nosso curso intensivo de WEB, este é apenas o início.
```

- Adicione uma imagem _img_ com o seguinte link _src_

```
https://ichef.bbci.co.uk/news/640/cpsprodpb/1438B/production/_102672828_hi048321534-1.jpg
- Adicione um segundo parágrafo *p*
```

- Adicione um parágrafo _p_

```
Começamos com trabalhando com títulos, parágrafos e imagem.
```

- Adicione um segundo parágrafo _p_

```
Mas, tem bastante coisa por ae...
```

- Adicione a seguinte citação _blockquote_

```
O céu é o limite.
```

---

## Aula 02 - Formatação de texto

### Crie uma pagina HTML

#### _head_

- Insira o _title_

```
Módulo 01 - HTML | Aula 02 - Formatação de texto

```

#### _body_

- Adicione o seguinte título _h1_

```
Redigindo Texto de artigo
```

- Adicione o seguinte subtitulo com _h2_

```
Manipulando informação como no Word
```

- Adicione outro parágrafo _p_

```
Vamos lidar com enfases no texto para aprender outras manipulações
```

- Dentro do mesmo ao _p_ insira uma quebra de linha no final _br_

- Abaixo, insira o texto com destaque sublinhado _ins_

```
Para dar enfase gostaria de sublinhar o texto para chamar a atenção.
```

- Abaixo, insira o texto com destaque em itálico _em_

```
Para dar enfase gostaria de usar italico como a torre de pisa.
```

- OBS: A tag _i_ (italic) funciona da mesma maneira que _em_, porém esta \*obsoleta e tem sido utilizada para referenciar icones. Portanto prefira sempre _em_ para inclinar o texto.

- Abaixo, insira o texto com destaque em negrito _strong_

```
Para dar enfase gostaria de negritar para chamar bastante atenção e fixar saltar aos olhos.
```

- OBS: A tag _b_ (bold - negrito em inglês) pasa pelo mesmo processo \*obsoleto de _i_, por tanto prefira usar _strong_

**\* Obsoleto:** Em programação, este termo é utilizado para referir-se a algo que vai cair em desuso e não tera mais suporte, ou seja sera descontinuado na próxima versão ou posteriormente, em outras palavras, "vai morrer".
Evite utilizar quaisquer coisas obsoletas para que o aplicativo não pare de funcionar numa futura atualização.

- Abaixo, insira o texto com destaque com o marcador _mark_

```
Para dar enfase gostaria de marcar a informação com caneta marca-texto.
```

- Abaixo, insira o texto com o destaque riscado _del_

```
Para dar enfase gostaria anular tudo que escrevi antes com esse risco.
```

- Ao lado, insira o texto superescrito _sup_

```
exponencial.
```

- Abaixo, insira o texto (sempre usando quebra de linha _br_)

```
Algumas informações
```

- Ao lado, insira o texto sobrescrito _sub_

```
sobrescritas.
```

---

## Aula 3 - Redigindo texto formal

### Crie uma pagina HTML

#### _head_

- Insira o _title_

```
Módulo 01 - HTML | Aula 02 - Formatação de texto

```

#### _body_

- Adicione um parágrafo _p_

```
Como ja dizia Platão:
```

- Adicione ao _p_ a seguinte citação _blockquote_ ou _q_

```
A necessidade que é a mãe da invenção.
```

- Abaixo, outro parágrafo _p_

```
Até o momentos estávamos trabalhando com parágrafos separados, mas agora vamos começar a usar quebra de linha para não sair do tema.
```

- Dentro do mesmo ao _p_ insira uma quebra de linha no final _br_

- Abaixo, continue com o texto

```
Até o momentos estávamos trabalhando com parágrafos separados, mas agora vamos começar a usar quebra de linha para não sair do tema.
```

- Dentro do mesmo ao _p_ insira uma quebra de linha no final _br_

- Abaixo, continue com o texto

```
Esta é a primeira quebra de linha sem paragrafo para continuar um assunto.
```

- Dentro do mesmo ao _p_ insira uma quebra de linha _br_ no final
- Abaixo, continue com o texto

```
Esta é a última quebra de linha para encerrar o assunto.
```

- Adicione o sequinte parágrafo _p_ e inclui uma abreviação _abbr_ e um **atributo** _title_ passe o mouse por cima e verá a descrição da abreviatura.

```
<p>O Conselho Regional <abbr title="Ordem dos Musicos do Brasil">OMB</abbr> disse que estão abertas as inscrições para os Cursos de Música.</ p>
```

- Adicione um parágrafo _p_ e inclua endereço _abbr_ abaixo

```
Av. Alm. Barroso, 72<br>
Centro<br>
Rio de Janeiro<br>
RJ<br>
20031-001<br>
Box 564, Disneyland<br>
BR
```
