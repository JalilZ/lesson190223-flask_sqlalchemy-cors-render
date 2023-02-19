# Very good flask template
## contains:
### sqlalchemy
### CORS


# Update DB create 
    with app.app_context():
        db.create_all()
        app.run(debug=True)


# Run:
    create a virtual enviroment
    py -m virtualenv myenv

# activate:
    env\script\activiate

# prepare the environment
    pip install -r .\requirements.txt
    flask run