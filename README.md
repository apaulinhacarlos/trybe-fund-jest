# Boas vindas ao repositório do projeto de Jest Assíncrono e Mocking!

Projeto desenvolvido por mim durante o curso de Desenvolvimento Web na <a href="https://www.betrybe.com/">Trybe</a> para fins educacionais e divulgado publicamente como portfólio de aprendizado. 

---

## Desenvolvimento

Neste projeto eu implementei testes utilizando o **Jest** para verificar se uma série de funções estão funcionando corretamente. Eu coloquei em prática todo o conteúdo que aprendi sobre Jest assíncrono e Mocks aplicados a testes em Javascript.

Eu fui capaz de:

- Escrever testes para funções assíncronas;
- Aplicar os seus conhecimentos acerca de testes utilizando o Jest;
- "Mockar" funções;
- "Mockar" APIs;

---

## Rodando o projeto localmente

Para rodar o projeto em sua máquina, abra seu terminal, crie um diretório no local de sua preferência com o comando `mkdir` e acesse o diretório criado com o comando `cd`:

```bash
mkdir meu-diretorio
cd meu-diretorio
```

Clone o projeto com o comando `git clone`:

```bash
git clone git@github.com:apaulinhacarlos/trybe-fund-jest.git
```

Acesse o diretório do projeto com o comando `cd`:

```bash
cd trybe-fund-jest
```

Instale as dependencias do projeto com o comando `npm install`:

```bash
npm install
```

Por fim, utilize o comando `npm test` para fazer os testes.

```bash
npm test
```

---

## Requisitos

### 1 - Crie testes para uma função assíncrona

Complete os testes do arquivo `test/asyncJest.spec.js` para que funcionem com código assíncrono.

### 2 - Crie um "Mock" no arquivo test/mockFunctions.spec.js

Crie mock functions no arquivo `test/mockFunctions.spec.js` para que os testes mockados 'sobrescrevam' o código definido na pasta `src`. A idéia é que as funções criadas a partir do Jest tenham prioridade na sua execução.

### 3 - Crie um Mock para o retorno da API

Crie uma API mock no arquivo `test/mockApi.spec.js` para que os testes do Jest utilizem retornos de API fixos e independentes de requisições.

Exemplo de resposta da API randomuser.me:

```js

{
  gender: 'female',
  name: { title: 'Ms', first: 'Deborah', last: 'Hanson' },
  location: {
    street: { number: 1299, name: 'Rochestown Road' },
    city: 'Birr',
    state: 'Wicklow',
    country: 'Ireland',
    postcode: 16223,
    coordinates: { latitude: '26.2451', longitude: '45.2995' },
    timezone: {
      offset: '+5:30',
      description: 'Bombay, Calcutta, Madras, New Delhi'
    }
  },
  email: 'deborah.hanson@example.com',
  login: {
    uuid: '45db2b1f-1c9a-4a80-9572-e46614f86c30',
    username: 'bluewolf366',
    password: 'iverson3',
    salt: 'XKOOGc2x',
    md5: '8cb7b4686f3869247b3ed189de780ea6',
    sha1: 'c24641f415cf36f4494ea4007fb3d77b47a6aad5',
    sha256: 'a7bdd079ead0adf21f30cee5b94e5581a9fa0d5fc8b3c1881dbc864dabc55a80'
  },
  dob: { date: '1965-10-01T06:35:49.694Z', age: 55 },
  registered: { date: '2009-02-11T05:48:39.772Z', age: 11 },
  phone: '021-953-7205',
  cell: '081-160-6277',
  id: { name: 'PPS', value: '0109675T' },
  picture: {
    large: 'https://randomuser.me/api/portraits/women/7.jpg',
    medium: 'https://randomuser.me/api/portraits/med/women/7.jpg',
    thumbnail: 'https://randomuser.me/api/portraits/thumb/women/7.jpg'
  },
  nat: 'IE'
}

```

### 4 - Crie funções no arquivo test/setupTeardown.spec.js

Intercale funções entre os testes definidos no arquivo `test/setupTeardown.spec.js`.

---

#### Todos os direitos relativos a essa obra, como reprodução, alteração, distribuição comercialização, pertencem à <a href="https://www.betrybe.com/">Trybe</a> e só podem ser utilizados com sua autorização.
