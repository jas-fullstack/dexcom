{
	"info": {
		"_postman_id": "50b30103-02b1-4c75-88b5-e3bfb748f5b3",
		"name": "dexcom",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "21595879"
	},
	"item": [
		{
			"name": "https://sandbox-api.dexcom.com/v2/oauth2/token",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "urlencoded",
					"urlencoded": [
						{
							"key": "grant_type",
							"value": "authorization_code",
							"type": "text"
						},
						{
							"key": "code",
							"value": "533d33c28705a6c8f06c2a3fde87da30",
							"type": "text"
						},
						{
							"key": "redirect_uri",
							"value": " ",
							"type": "text"
						},
						{
							"key": "client_id",
							"value": "",
							"type": "text"
						},
						{
							"key": "client_secret",
							"value": "",
							"type": "text"
						}
					]
				},
				"url": {
					"raw": "https://sandbox-api.dexcom.com/v2/oauth2/token",
					"protocol": "https",
					"host": [
						"sandbox-api",
						"dexcom",
						"com"
					],
					"path": [
						"v2",
						"oauth2",
						"token"
					]
				}
			},
			"response": []
		},
		{
			"name": "https://sandbox-api.dexcom.com/v2/users/self/egvs?startDate=2023-01-01T09%3A12%3A35&endDate=2023-01-03T09%3A12%3A35",
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "Authorization",
						"value": "",
						"type": "text"
					}
				],
				"url": {
					"raw": "https://sandbox-api.dexcom.com/v2/users/self/egvs?startDate=2023-01-01T09%3A12%3A35&endDate=2023-01-03T09%3A12%3A35",
					"protocol": "https",
					"host": [
						"sandbox-api",
						"dexcom",
						"com"
					],
					"path": [
						"v2",
						"users",
						"self",
						"egvs"
					],
					"query": [
						{
							"key": "startDate",
							"value": "2023-01-01T09%3A12%3A35"
						},
						{
							"key": "endDate",
							"value": "2023-01-03T09%3A12%3A35"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "https://sandbox-api.dexcom.com/v3/users/self/alerts?startDate=2023-01-01T09:12:35&endDate=2023-01-30T09:12:35",
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "Authorization",
						"value": "",
						"type": "text"
					}
				],
				"url": {
					"raw": "https://sandbox-api.dexcom.com/v3/users/self/alerts?startDate=2023-01-01T09:12:35&endDate=2023-01-30T09:12:35",
					"protocol": "https",
					"host": [
						"sandbox-api",
						"dexcom",
						"com"
					],
					"path": [
						"v3",
						"users",
						"self",
						"alerts"
					],
					"query": [
						{
							"key": "startDate",
							"value": "2023-01-01T09:12:35"
						},
						{
							"key": "endDate",
							"value": "2023-01-30T09:12:35"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "https://sandbox-api.dexcom.com/v3/users/self/calibrations?startDate=2023-01-01T09%3A12%3A35&endDate=2023-01-30T09%3A12%3A35",
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "Authorization",
						"value": "",
						"type": "text"
					}
				],
				"url": {
					"raw": "https://sandbox-api.dexcom.com/v3/users/self/calibrations?startDate=2023-01-01T09%3A12%3A35&endDate=2023-01-30T09%3A12%3A35",
					"protocol": "https",
					"host": [
						"sandbox-api",
						"dexcom",
						"com"
					],
					"path": [
						"v3",
						"users",
						"self",
						"calibrations"
					],
					"query": [
						{
							"key": "startDate",
							"value": "2023-01-01T09%3A12%3A35"
						},
						{
							"key": "endDate",
							"value": "2023-01-30T09%3A12%3A35"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "https://sandbox-api.dexcom.com/v3/users/self/events?startDate=2023-01-01T09%3A12%3A35&endDate=2023-01-30T09%3A12%3A35",
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "Authorization",
						"value": "",
						"type": "text"
					}
				],
				"url": {
					"raw": "https://sandbox-api.dexcom.com/v3/users/self/events?startDate=2023-01-01T09%3A12%3A35&endDate=2023-01-30T09%3A12%3A35",
					"protocol": "https",
					"host": [
						"sandbox-api",
						"dexcom",
						"com"
					],
					"path": [
						"v3",
						"users",
						"self",
						"events"
					],
					"query": [
						{
							"key": "startDate",
							"value": "2023-01-01T09%3A12%3A35"
						},
						{
							"key": "endDate",
							"value": "2023-01-30T09%3A12%3A35"
						}
					]
				}
			},
			"response": []
		},
		{
			"name": "https://sandbox-api.dexcom.com/v2/oauth2/login?client_id=G26enpX0KSyGE23t1bk8iKs5uIsTQML8&redirect_uri= &response_type=code&scope=offline_access",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://sandbox-api.dexcom.com/v2/oauth2/login?client_id=G26enpX0KSyGE23t1bk8iKs5uIsTQML8&redirect_uri= &response_type=code&scope=offline_access",
					"protocol": "https",
					"host": [
						"sandbox-api",
						"dexcom",
						"com"
					],
					"path": [
						"v2",
						"oauth2",
						"login"
					],
					"query": [
						{
							"key": "client_id",
							"value": ""
						},
						{
							"key": "redirect_uri",
							"value": " "
						},
						{
							"key": "response_type",
							"value": "code"
						},
						{
							"key": "scope",
							"value": "offline_access"
						}
					]
				}
			},
			"response": []
		}
	]
}
