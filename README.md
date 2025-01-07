# Oklid-mesafes-
points = [(1, 2), (4, 6), (5, 8), (7, 9)]

def euclideanDistance(point1, point2) :
    return ((point2[0] - point[0])**2 +(point2[1] - point1[1])**2)**0.5

distances = [euclideanDistance(points[i], points[j]) for i in range(len(points)) for j in range(i + 1, len(points))]

print(min(distances))
