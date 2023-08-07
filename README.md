# 🚀 Go CRUD REST API
## 🔨 Made with Go/Gin/Gorm/Postgres 
# Prerequisite
You must have Go, Npm & Docker installed, run these commands to check:
```
go version
```

```
npm -v
```

```
docker -v
```

# :arrow_forward: Running the server
You just have to run Make, a setup script will set everything up for you :) 
```
make serve
```

# :eight_spoked_asterisk: Restful API
![](/assets/img/swagger.png)
# :green_book: OpenAPI Specification
## Version: 1.0


**License:** [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)

## /products

#### GET
##### Summary:

List products

##### Description:

get products

##### Responses

| Code | Description | Schema |
| ---- | ----------- | ------ |
| 200 | OK | [ [product.Product](#product.Product) ] |
| 400 | Bad Request |  |
| 404 | Not Found |  |
| 500 | Internal Server Error |  |


## /products

#### POST
##### Summary:

creates a product

##### Description:

creates a product

##### Responses

| Code | Description | Schema |
| ---- | ----------- | ------ |
| 200 | OK | [product.Product](#product.Product) |
| 400 | Bad Request |  |
| 404 | Not Found |  |
| 500 | Internal Server Error |  |

## /products/{id}

#### DELETE
##### Summary:

deletes a product

##### Description:

deletes a product

##### Responses

| Code | Description | Schema |
| ---- | ----------- | ------ |
| 200 | OK | [product.Product](#product.Product) |
| 400 | Bad Request |  |
| 404 | Not Found |  |
| 500 | Internal Server Error |  |


## /products/{id}

#### GET
##### Summary:

finds one product by ID

##### Description:

gets product

##### Responses

| Code | Description | Schema |
| ---- | ----------- | ------ |
| 200 | OK | [product.Product](#product.Product) |
| 400 | Bad Request |  |
| 404 | Not Found |  |
| 500 | Internal Server Error |  |


## /products/{id}

#### POST
##### Summary:

updates a product

##### Description:

updates a product

##### Responses

| Code | Description | Schema |
| ---- | ----------- | ------ |
| 200 | OK | [product.Product](#product.Product) |
| 400 | Bad Request |  |
| 404 | Not Found |  |
| 500 | Internal Server Error |  |

### Models

#### product.Product

| Name | Type | Description | Required |
| ---- | ---- | ----------- | -------- |
| code | string |  | No |
| createdAt | string |  | No |
| deletedAt | [gorm.DeletedAt](#gorm.DeletedAt) |  | No |
| id | integer |  | No |
| price | integer |  | No |
| updatedAt | string |  | No |


