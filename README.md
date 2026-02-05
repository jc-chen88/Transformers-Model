# Transformers-Model
This project applies the transformers architecture to the ETTh (Electricity Transformer Temperature – hourly) dataset for multivariate time-series forecasting. Done in R using the Keras and Torch packages. Here is a quick overview of the process:

    1. **Preprocessing the data** - loading the data set and affirming the 
    correct data types
    
    2. **Sequence generation** - generating sequences that will be used for 
    testing and training
    
    3. **Positional encoding** - gives each position/time step a unique 
    signal so the model can distinguish between the positions. This is done by 
    creating a unique vector for each position the sequence with sine and 
    cosine functions.
    
    4. **Transformers model** - create a Transformer encoder model that sets up 
    model layers and parameters and processes positional encoding provided 
    before
    
    5. **Traing and testing** - model will be trained using epochs and will be 
    evaluated using MSE loss.
