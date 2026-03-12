# OneHotEncoder
from sklearn.preprocessing import OneHotEncoder
color = [["black"],["purple"],["pink"]]
encoder = OneHotEncoder()
result = encoder.fit_transform(color)
print(result.toarray())
