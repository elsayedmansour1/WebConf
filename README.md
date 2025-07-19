# WebConf

always after made any change in nginx.conf or in index.html
run 

``linux
sudo nginx -t && sudo systemctl reload nginx
``

example how to use the add_route.py script in output directory

python add_route.py <route_name> "<display_name>" [--input input.html] [--output output.html]

python add_route.py ipv6Subnet "IPv6 Subnet" --input ../index.html --output index.html