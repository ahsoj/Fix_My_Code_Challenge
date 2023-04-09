# Fix the route path

$ python -m api.v1.app 
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
....

$ curl -XGET http://0.0.0.0:5000/api/v1/status
{
  "error": "Not found"
}
$

