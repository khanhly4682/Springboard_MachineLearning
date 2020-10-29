# Plot Actual and Predicted Scatterplot
    _, ax = plt.subplots()
    ax.scatter(x = range(0, y_test.size), y=y_test, c = 'blue', label = 'Actual', alpha = 0.3)
    ax.scatter(x = range(0, y_pred.size), y=y_pred, c = 'red', label = 'Predicted', alpha = 0.3)
    plt.title('Actual and predicted values')
    plt.legend()
    plt.show()

# Residual plots:
http://docs.statwing.com/interpreting-residual-plots-to-improve-your-regression/


# Basic commands:
# 1. Upgrade pip:
- Open Window > "Anaconda Prompt", type :
python -m pip install --upgrade pip

# 2. Check version of pip:
cmd > pip --version

# 3. Update pip
conda update pip

# 4. Install Keras
Open Window > Anaconda Prompt > pip install keras

# 4. Install a package on PyCharm
- File/Settings/ Project/ Project Interpreter > press "+" sign on the right, enter the package name.

5. Create __init__ package, main.py and how to call modules.
https://toidicode.com/packages-trong-python-355.html#:~:text=%C4%90%E1%BB%83%20t%E1%BA%A1o%20ra%20m%E1%BB%99t%20package,ch%C3%BAng%20ta%20import%20package%20%C4%91%C3%B3.
