# Plot Actual and Predicted Scatterplot
    _, ax = plt.subplots()
    ax.scatter(x = range(0, y_test.size), y=y_test, c = 'blue', label = 'Actual', alpha = 0.3)
    ax.scatter(x = range(0, y_pred.size), y=y_pred, c = 'red', label = 'Predicted', alpha = 0.3)
    plt.title('Actual and predicted values')
    plt.legend()
    plt.show()
