from PIL import Image as pict

def resize_picture(picture_way,width,length):
    
    picture = pict.open(picture_way)
    resized_picture = picture.resize((width, length))
    save_way = "resized_picture.png"
    resized_picture.save(save_way)
    
    return save_way

def rotate_picture(picture_way, corner):
    
    picture = pict.open(picture_way)
    rotated_picture = picture.rotate(corner)
    save_way = "rotated_picture.png"
    rotated_picture.save(save_way)
    
    return save_way
