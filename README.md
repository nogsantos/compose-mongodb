# Docker compose MongoDB

A Docker compose mongo db container

## Requirements

<table>
  <thead>
    <tr>
        <th>Tool</th>
        <th>Min. Version</th>
    </tr>
  </thead>
  <tbody>
      <tr>
        <td>Docker</td>
        <td>>= 18.9.x</td>
      </tr>
      <tr>
        <td>docker-compose</td>
        <td>>= 1.23.x</td>
      </tr>
  </tbody>
</table>

## Container

<table>
  <thead>
    <tr>
        <th>Image</th>
        <th>Version</th>
    </tr>
  </thead>
  <tbody>
      <tr>
        <td>Ubuntu</td>
        <td>18.04</td>
      </tr>
      <tr>
        <td>MongoDB</td>
        <td>4.0.6</td>
      </tr>
  </tbody>
</table>

## Setup

### Run

```bash
$ docker-compose up -d
```

### logs

```bash
$ docker logs -f mongodb
```
