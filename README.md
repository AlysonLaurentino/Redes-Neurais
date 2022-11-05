# Projeto Final - Modelos Preditivos Conexionistas

### Alyson Patrick Sobrinho Lima Laurentino

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
<br>Deteção de Objetos|YOLOv5|Tensorflow|

## Performance

O modelo treinado possui performance de **>80%**.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ``  Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      0/299       2.4G    0.07757    0.02922    0.03285         30        640: 100% 12/12 [00:05<00:00,  2.22it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  2.43it/s]
                   all         26         26   0.000133        0.1   0.000108   1.08e-05

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      1/299      2.97G    0.06564    0.03079     0.0341         26        640: 100% 12/12 [00:03<00:00,  3.11it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  2.98it/s]
                   all         26         26    0.00437       0.95      0.132     0.0379

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      2/299      2.97G    0.05686    0.02861    0.02968         24        640: 100% 12/12 [00:02<00:00,  4.67it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  5.63it/s]
                   all         26         26     0.0421      0.406      0.145     0.0546

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      3/299      2.97G    0.04838    0.02692    0.02891         30        640: 100% 12/12 [00:02<00:00,  5.84it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.22it/s]
                   all         26         26        0.4      0.283      0.218      0.125

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      4/299      2.97G    0.04568    0.02474    0.02684         27        640: 100% 12/12 [00:01<00:00,  6.11it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.78it/s]
                   all         26         26      0.527      0.227      0.307      0.174

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      5/299      2.97G    0.04686    0.02279    0.02611         30        640: 100% 12/12 [00:01<00:00,  6.03it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.94it/s]
                   all         26         26      0.648       0.42       0.47      0.236

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      6/299      2.97G    0.04266    0.02015    0.02298         24        640: 100% 12/12 [00:01<00:00,  6.16it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.13it/s]
                   all         26         26      0.906      0.238      0.403      0.217

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      7/299      2.97G    0.04192    0.01975     0.0223         31        640: 100% 12/12 [00:01<00:00,  6.05it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.50it/s]
                   all         26         26      0.711      0.316      0.483      0.274

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      8/299      2.97G     0.0501    0.01807    0.02596         34        640: 100% 12/12 [00:01<00:00,  6.23it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.05it/s]
                   all         26         26      0.958      0.237      0.457      0.218

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
      9/299      2.97G    0.03992    0.01673       0.02         26        640: 100% 12/12 [00:01<00:00,  6.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.90it/s]
                   all         26         26      0.923      0.288      0.493      0.278

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     10/299      2.97G    0.04574    0.01682    0.02486         28        640: 100% 12/12 [00:01<00:00,  6.15it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.28it/s]
                   all         26         26      0.828      0.267      0.391      0.188

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     11/299      2.97G    0.03754    0.01879    0.01905         30        640: 100% 12/12 [00:01<00:00,  6.14it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.83it/s]
                   all         26         26      0.786      0.422      0.579      0.241

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     12/299      2.97G    0.04375    0.01743    0.01822         26        640: 100% 12/12 [00:01<00:00,  6.19it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.75it/s]
                   all         26         26       0.76      0.422      0.605      0.301

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     13/299      2.97G    0.03595    0.01658    0.01937         26        640: 100% 12/12 [00:01<00:00,  6.07it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.05it/s]
                   all         26         26      0.732        0.5      0.625      0.317

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     14/299      2.97G    0.03115    0.01654    0.01712         29        640: 100% 12/12 [00:01<00:00,  6.24it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.23it/s]
                   all         26         26      0.531      0.486      0.532      0.203

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     15/299      2.97G    0.03614    0.01709    0.01629         34        640: 100% 12/12 [00:02<00:00,  5.94it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.78it/s]
                   all         26         26      0.604      0.504      0.631      0.282

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     16/299      2.97G    0.03196    0.01647    0.01704         29        640: 100% 12/12 [00:01<00:00,  6.23it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.15it/s]
                   all         26         26      0.471      0.572      0.477      0.157

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     17/299      2.97G    0.03454    0.01598    0.02149         27        640: 100% 12/12 [00:01<00:00,  6.17it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.62it/s]
                   all         26         26      0.588      0.622      0.639      0.338

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     18/299      2.97G    0.02907    0.01669    0.01502         32        640: 100% 12/12 [00:01<00:00,  6.24it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.07it/s]
                   all         26         26      0.298      0.694      0.617      0.299

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     19/299      2.97G    0.03134    0.01653    0.01497         31        640: 100% 12/12 [00:01<00:00,  6.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.04it/s]
                   all         26         26      0.441      0.665      0.608      0.344

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     20/299      2.97G     0.0274     0.0146    0.01613         30        640: 100% 12/12 [00:01<00:00,  6.16it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.25it/s]
                   all         26         26      0.264      0.672      0.469      0.231

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     21/299      2.97G    0.02915    0.01687    0.01412         27        640: 100% 12/12 [00:02<00:00,  5.93it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.58it/s]
                   all         26         26      0.435      0.522      0.575      0.262

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     22/299      2.97G    0.02986    0.01597    0.01263         30        640: 100% 12/12 [00:01<00:00,  6.00it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.15it/s]
                   all         26         26      0.345      0.823       0.48      0.246

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     23/299      2.97G    0.02784     0.0159    0.01424         36        640: 100% 12/12 [00:01<00:00,  6.21it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.57it/s]
                   all         26         26      0.374      0.635      0.447      0.257

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     24/299      2.97G    0.03166     0.0155     0.0147         22        640: 100% 12/12 [00:01<00:00,  6.17it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.33it/s]
                   all         26         26      0.287      0.587      0.412      0.164

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     25/299      2.97G     0.0279    0.01414    0.01025         28        640: 100% 12/12 [00:02<00:00,  5.60it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.66it/s]
                   all         26         26      0.482      0.737      0.561      0.331

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     26/299      2.97G    0.03527    0.01538    0.01087         35        640: 100% 12/12 [00:02<00:00,  5.99it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.96it/s]
                   all         26         26      0.453      0.783      0.548       0.29

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     27/299      2.97G     0.0265    0.01361    0.01019         27        640: 100% 12/12 [00:01<00:00,  6.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.53it/s]
                   all         26         26       0.65      0.833      0.681      0.405

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     28/299      2.97G    0.03138    0.01479    0.01067         31        640: 100% 12/12 [00:03<00:00,  3.51it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  4.37it/s]
                   all         26         26      0.675      0.699      0.751      0.366

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     29/299      2.97G    0.02476    0.01504    0.01139         31        640: 100% 12/12 [00:03<00:00,  3.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:02<00:00,  1.26s/it]
                   all         26         26      0.599      0.873      0.703      0.385

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     30/299      2.97G    0.02304    0.01551   0.008062         29        640: 100% 12/12 [00:02<00:00,  5.84it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.63it/s]
                   all         26         26      0.725      0.887      0.739      0.351

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     31/299      2.97G    0.02602    0.01491   0.008473         26        640: 100% 12/12 [00:02<00:00,  5.98it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.29it/s]
                   all         26         26      0.725      0.771        0.8      0.537

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     32/299      2.97G    0.02975    0.01538    0.01399         23        640: 100% 12/12 [00:01<00:00,  6.11it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.88it/s]
                   all         26         26      0.677       0.78      0.748      0.484

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     33/299      2.97G     0.0267     0.0144   0.008501         29        640: 100% 12/12 [00:02<00:00,  5.93it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.99it/s]
                   all         26         26       0.62      0.807      0.737      0.384

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     34/299      2.97G    0.03064     0.0135   0.007222         25        640: 100% 12/12 [00:02<00:00,  5.95it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.73it/s]
                   all         26         26      0.521      0.695      0.683      0.281

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     35/299      2.97G    0.02778    0.01307   0.009787         24        640: 100% 12/12 [00:01<00:00,  6.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.08it/s]
                   all         26         26      0.669       0.76      0.781      0.498

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     36/299      2.97G    0.02457    0.01433   0.008293         29        640: 100% 12/12 [00:02<00:00,  5.79it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.02it/s]
                   all         26         26      0.671      0.698      0.763      0.459

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     37/299      2.97G    0.02427    0.01274   0.007064         27        640: 100% 12/12 [00:02<00:00,  5.81it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.36it/s]
                   all         26         26      0.669      0.716      0.713      0.417

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     38/299      2.97G    0.02841    0.01538   0.008243         25        640: 100% 12/12 [00:02<00:00,  5.98it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.30it/s]
                   all         26         26      0.677        0.8      0.743      0.495

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     39/299      2.97G    0.03154    0.01353   0.008022         27        640: 100% 12/12 [00:01<00:00,  6.03it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.42it/s]
                   all         26         26      0.737      0.652      0.726       0.49

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     40/299      2.97G    0.02882    0.01402   0.008205         32        640: 100% 12/12 [00:02<00:00,  5.92it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.65it/s]
                   all         26         26      0.735      0.789      0.765      0.448

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     41/299      2.97G    0.02654    0.01357   0.007166         23        640: 100% 12/12 [00:02<00:00,  5.98it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.23it/s]
                   all         26         26      0.755      0.651      0.745      0.414

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     42/299      2.97G    0.02422    0.01406    0.01033         30        640: 100% 12/12 [00:01<00:00,  6.05it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.44it/s]
                   all         26         26      0.635      0.793      0.745      0.358

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     43/299      2.97G    0.02581    0.01447    0.01275         33        640: 100% 12/12 [00:01<00:00,  6.17it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.66it/s]
                   all         26         26      0.761      0.692      0.695      0.328

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     44/299      2.97G    0.02483    0.01339   0.006546         27        640: 100% 12/12 [00:01<00:00,  6.04it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.36it/s]
                   all         26         26      0.655      0.781      0.719      0.341

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     45/299      2.97G    0.02683    0.01402   0.006358         28        640: 100% 12/12 [00:01<00:00,  6.05it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.83it/s]
                   all         26         26      0.606      0.798      0.694      0.417

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     46/299      2.97G     0.0261    0.01394   0.005868         40        640: 100% 12/12 [00:01<00:00,  6.04it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.26it/s]
                   all         26         26       0.65      0.861      0.758      0.498

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     47/299      2.97G    0.02111    0.01356   0.005622         36        640: 100% 12/12 [00:01<00:00,  6.18it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.77it/s]
                   all         26         26      0.657      0.807      0.717      0.367

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     48/299      2.97G    0.02635    0.01339   0.006208         27        640: 100% 12/12 [00:01<00:00,  6.05it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.26it/s]
                   all         26         26      0.719      0.799      0.777      0.439

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     49/299      2.97G    0.02007    0.01282   0.007337         30        640: 100% 12/12 [00:01<00:00,  6.09it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.07it/s]
                   all         26         26      0.718       0.82      0.797      0.593

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     50/299      2.97G    0.02052    0.01305   0.004872         35        640: 100% 12/12 [00:01<00:00,  6.15it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.17it/s]
                   all         26         26      0.709      0.798      0.764      0.582

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     51/299      2.97G    0.02062    0.01292   0.005167         30        640: 100% 12/12 [00:02<00:00,  5.99it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.48it/s]
                   all         26         26      0.771      0.697      0.784      0.557

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     52/299      2.97G    0.02752     0.0137   0.007665         36        640: 100% 12/12 [00:02<00:00,  5.86it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.25it/s]
                   all         26         26      0.617      0.756      0.739       0.44

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     53/299      2.97G    0.02075    0.01317   0.006897         30        640: 100% 12/12 [00:02<00:00,  5.91it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.34it/s]
                   all         26         26      0.759      0.884      0.825      0.478

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     54/299      2.97G    0.02864    0.01317   0.008233         23        640: 100% 12/12 [00:01<00:00,  6.06it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.94it/s]
                   all         26         26       0.78      0.784      0.824      0.525

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     55/299      2.97G    0.02296    0.01274   0.004677         33        640: 100% 12/12 [00:01<00:00,  6.09it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.60it/s]
                   all         26         26      0.743      0.891      0.821      0.417

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     56/299      2.97G    0.02271    0.01401   0.006539         24        640: 100% 12/12 [00:02<00:00,  5.99it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.26it/s]
                   all         26         26      0.725      0.861      0.841      0.511

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     57/299      2.97G    0.02209    0.01399   0.005393         31        640: 100% 12/12 [00:02<00:00,  5.89it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  9.03it/s]
                   all         26         26      0.684      0.762      0.723      0.364

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     58/299      2.97G     0.0225    0.01322   0.003746         25        640: 100% 12/12 [00:01<00:00,  6.11it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.54it/s]
                   all         26         26      0.816      0.853      0.859      0.514

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     59/299      2.97G    0.02252    0.01367   0.008261         31        640: 100% 12/12 [00:01<00:00,  6.20it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.12it/s]
                   all         26         26      0.677      0.815      0.822      0.427

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     60/299      2.97G    0.01993    0.01231   0.005955         35        640: 100% 12/12 [00:02<00:00,  5.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.50it/s]
                   all         26         26      0.744      0.729      0.841      0.451

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     61/299      2.97G    0.02598    0.01255   0.005279         29        640: 100% 12/12 [00:01<00:00,  6.01it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.70it/s]
                   all         26         26      0.747      0.751       0.84      0.432

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     62/299      2.97G    0.02177    0.01278   0.007032         33        640: 100% 12/12 [00:01<00:00,  6.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.42it/s]
                   all         26         26      0.808      0.911      0.887      0.552

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     63/299      2.97G    0.02178      0.013   0.005102         27        640: 100% 12/12 [00:01<00:00,  6.10it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.40it/s]
                   all         26         26      0.744      0.879      0.865      0.568

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     64/299      2.97G    0.01857    0.01205   0.003859         30        640: 100% 12/12 [00:01<00:00,  6.03it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.68it/s]
                   all         26         26      0.798      0.893      0.882      0.601

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     65/299      2.97G    0.02502     0.0121   0.004552         34        640: 100% 12/12 [00:01<00:00,  6.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.53it/s]
                   all         26         26      0.828      0.878      0.897      0.529

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     66/299      2.97G     0.0204    0.01279   0.004077         28        640: 100% 12/12 [00:01<00:00,  6.06it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.44it/s]
                   all         26         26      0.722       0.84      0.805      0.495

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     67/299      2.97G    0.01943    0.01282   0.003459         33        640: 100% 12/12 [00:01<00:00,  6.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.61it/s]
                   all         26         26       0.66      0.921      0.789      0.459

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     68/299      2.97G    0.02087    0.01301   0.004771         28        640: 100% 12/12 [00:01<00:00,  6.03it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.26it/s]
                   all         26         26      0.736      0.895      0.822       0.53

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     69/299      2.97G    0.01955    0.01259    0.00494         27        640: 100% 12/12 [00:01<00:00,  6.15it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.18it/s]
                   all         26         26       0.72      0.908      0.829      0.503

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     70/299      2.97G    0.01908    0.01184   0.003266         32        640: 100% 12/12 [00:01<00:00,  6.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.58it/s]
                   all         26         26      0.671      0.929      0.797       0.42

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     71/299      2.97G    0.02367    0.01302   0.008413         28        640: 100% 12/12 [00:01<00:00,  6.11it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.34it/s]
                   all         26         26      0.839      0.719      0.787      0.553

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     72/299      2.97G    0.01841    0.01304   0.005098         26        640: 100% 12/12 [00:01<00:00,  6.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.47it/s]
                   all         26         26      0.741      0.766      0.772      0.492

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     73/299      2.97G    0.01763     0.0119   0.006208         24        640: 100% 12/12 [00:01<00:00,  6.02it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.42it/s]
                   all         26         26        0.7      0.708      0.731      0.511

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     74/299      2.97G    0.01645    0.01202   0.003733         24        640: 100% 12/12 [00:01<00:00,  6.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.89it/s]
                   all         26         26      0.711      0.797       0.75      0.517

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     75/299      2.97G    0.01915    0.01208   0.004921         24        640: 100% 12/12 [00:01<00:00,  6.16it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.60it/s]
                   all         26         26      0.782      0.864      0.836      0.557

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     76/299      2.97G     0.0174    0.01265   0.005185         25        640: 100% 12/12 [00:02<00:00,  5.96it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.57it/s]
                   all         26         26      0.733      0.872      0.836      0.518

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     77/299      2.97G    0.01912    0.01171   0.004908         28        640: 100% 12/12 [00:01<00:00,  6.11it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.91it/s]
                   all         26         26      0.736      0.891      0.753       0.45

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     78/299      2.97G    0.02098    0.01252   0.004418         28        640: 100% 12/12 [00:01<00:00,  6.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.09it/s]
                   all         26         26       0.66      0.838      0.723      0.547

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     79/299      2.97G    0.02265    0.01188   0.005451         37        640: 100% 12/12 [00:01<00:00,  6.19it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.01it/s]
                   all         26         26      0.755      0.855      0.806      0.516

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     80/299      2.97G    0.01897    0.01226   0.004117         31        640: 100% 12/12 [00:02<00:00,  6.00it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.32it/s]
                   all         26         26      0.725      0.798      0.807      0.549

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     81/299      2.97G    0.01729    0.01303   0.004348         33        640: 100% 12/12 [00:01<00:00,  6.14it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.86it/s]
                   all         26         26      0.714      0.757      0.799      0.536

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     82/299      2.97G     0.0258     0.0122   0.007959         25        640: 100% 12/12 [00:01<00:00,  6.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.48it/s]
                   all         26         26      0.724      0.866       0.81       0.59

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     83/299      2.97G    0.02853    0.01251    0.00411         27        640: 100% 12/12 [00:02<00:00,  5.96it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.41it/s]
                   all         26         26      0.695      0.779      0.748      0.479

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     84/299      2.97G    0.02372    0.01276    0.00502         29        640: 100% 12/12 [00:02<00:00,  5.97it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.25it/s]
                   all         26         26      0.637      0.803       0.73       0.49

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     85/299      2.97G    0.02073    0.01244   0.006111         30        640: 100% 12/12 [00:02<00:00,  5.89it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.63it/s]
                   all         26         26      0.655      0.857      0.755      0.541

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     86/299      2.97G    0.02097    0.01256   0.004486         29        640: 100% 12/12 [00:01<00:00,  6.05it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.49it/s]
                   all         26         26      0.669      0.779      0.735      0.472

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     87/299      2.97G    0.02165    0.01192   0.006022         23        640: 100% 12/12 [00:02<00:00,  5.96it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.22it/s]
                   all         26         26      0.639      0.741      0.685      0.388

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     88/299      2.97G    0.02004    0.01235   0.005911         27        640: 100% 12/12 [00:01<00:00,  6.07it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.28it/s]
                   all         26         26      0.662      0.692      0.733      0.481

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     89/299      2.97G    0.02145    0.01264    0.00646         28        640: 100% 12/12 [00:01<00:00,  6.05it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.13it/s]
                   all         26         26      0.786      0.675      0.762      0.444

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     90/299      2.97G    0.01908     0.0112   0.003444         23        640: 100% 12/12 [00:02<00:00,  4.90it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.53it/s]
                   all         26         26      0.728        0.8      0.844      0.459

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     91/299      2.97G    0.01895    0.01248   0.003261         30        640: 100% 12/12 [00:01<00:00,  6.19it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.82it/s]
                   all         26         26      0.722      0.754       0.83      0.483

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     92/299      2.97G    0.01651    0.01233    0.00374         32        640: 100% 12/12 [00:02<00:00,  5.67it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.53it/s]
                   all         26         26      0.789      0.693      0.803      0.487

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     93/299      2.97G    0.01696    0.01122   0.003563         23        640: 100% 12/12 [00:01<00:00,  6.20it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.89it/s]
                   all         26         26      0.699      0.765      0.819      0.524

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     94/299      2.97G    0.02109     0.0132    0.00469         30        640: 100% 12/12 [00:01<00:00,  6.01it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.64it/s]
                   all         26         26      0.782      0.792      0.846      0.578

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     95/299      2.97G    0.01806    0.01174   0.004139         30        640: 100% 12/12 [00:01<00:00,  6.09it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.22it/s]
                   all         26         26      0.802      0.839      0.816      0.493

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     96/299      2.97G    0.02218    0.01238   0.005203         27        640: 100% 12/12 [00:01<00:00,  6.19it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.78it/s]
                   all         26         26      0.729      0.727      0.755      0.544

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     97/299      2.97G    0.01909    0.01105   0.006965         32        640: 100% 12/12 [00:01<00:00,  6.09it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.28it/s]
                   all         26         26      0.729      0.705      0.745      0.527

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     98/299      2.97G    0.01725    0.01214   0.003065         32        640: 100% 12/12 [00:01<00:00,  6.04it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.74it/s]
                   all         26         26      0.715      0.755      0.758      0.441

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     99/299      2.97G    0.01682    0.01122    0.00358         31        640: 100% 12/12 [00:01<00:00,  6.17it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.25it/s]
                   all         26         26      0.728      0.763      0.743      0.458

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    100/299      2.97G    0.01953    0.01172   0.005837         24        640: 100% 12/12 [00:01<00:00,  6.15it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.33it/s]
                   all         26         26      0.725      0.706      0.755      0.429

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    101/299      2.97G    0.01978    0.01091   0.005943         27        640: 100% 12/12 [00:01<00:00,  6.09it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.14it/s]
                   all         26         26      0.739      0.725      0.739      0.481

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    102/299      2.97G    0.01873    0.01137   0.007078         21        640: 100% 12/12 [00:01<00:00,  6.08it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.12it/s]
                   all         26         26      0.684      0.872      0.773      0.496

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    103/299      2.97G    0.01706    0.01162   0.007453         28        640: 100% 12/12 [00:01<00:00,  6.11it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.54it/s]
                   all         26         26      0.723      0.761      0.789      0.526

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    104/299      2.97G    0.01909    0.01162   0.003882         30        640: 100% 12/12 [00:01<00:00,  6.05it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.62it/s]
                   all         26         26      0.686      0.799      0.814      0.585

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    105/299      2.97G    0.02292    0.01178   0.005811         27        640: 100% 12/12 [00:02<00:00,  5.80it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.71it/s]
                   all         26         26      0.704      0.757      0.777      0.499

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    106/299      2.97G     0.0238    0.01208   0.006534         26        640: 100% 12/12 [00:02<00:00,  5.87it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.92it/s]
                   all         26         26      0.748      0.748      0.791      0.561

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    107/299      2.97G    0.01786    0.01109   0.004044         27        640: 100% 12/12 [00:01<00:00,  6.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.13it/s]
                   all         26         26      0.768      0.745      0.806      0.538

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    108/299      2.97G    0.01734    0.01233   0.005748         28        640: 100% 12/12 [00:02<00:00,  5.93it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.20it/s]
                   all         26         26      0.771      0.829      0.833      0.591

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    109/299      2.97G    0.01865    0.01163   0.003208         28        640: 100% 12/12 [00:01<00:00,  6.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.92it/s]
                   all         26         26       0.76       0.84      0.862      0.516

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    110/299      2.97G    0.01829    0.01136   0.004931         31        640: 100% 12/12 [00:02<00:00,  5.94it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.94it/s]
                   all         26         26      0.774      0.853      0.833      0.568

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    111/299      2.97G     0.0184    0.01217   0.005175         31        640: 100% 12/12 [00:01<00:00,  6.19it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.39it/s]
                   all         26         26      0.779      0.766       0.81      0.504

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    112/299      2.97G    0.01575     0.0111   0.003028         27        640: 100% 12/12 [00:01<00:00,  6.18it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.29it/s]
                   all         26         26      0.774      0.768      0.804      0.517

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    113/299      2.97G    0.01654    0.01202   0.004134         34        640: 100% 12/12 [00:02<00:00,  5.96it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.78it/s]
                   all         26         26      0.762      0.773      0.804      0.457

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    114/299      2.97G    0.01631    0.01138    0.00455         23        640: 100% 12/12 [00:02<00:00,  4.88it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  4.53it/s]
                   all         26         26      0.779      0.771      0.808      0.461

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    115/299      2.97G    0.01975    0.01246   0.004287         24        640: 100% 12/12 [00:03<00:00,  3.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  4.81it/s]
                   all         26         26      0.749      0.815      0.791       0.49

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    116/299      2.97G    0.01555    0.01156   0.003265         30        640: 100% 12/12 [00:03<00:00,  3.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  4.93it/s]
                   all         26         26      0.824      0.806      0.792       0.51

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    117/299      2.97G    0.01622    0.01206   0.003931         29        640: 100% 12/12 [00:02<00:00,  5.84it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.21it/s]
                   all         26         26      0.703       0.83      0.798      0.564

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    118/299      2.97G    0.01485     0.0122   0.002743         32        640: 100% 12/12 [00:01<00:00,  6.08it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.12it/s]
                   all         26         26        0.7      0.827      0.793      0.593

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    119/299      2.97G    0.01547    0.01081   0.002795         35        640: 100% 12/12 [00:02<00:00,  6.00it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.14it/s]
                   all         26         26      0.689      0.867      0.796      0.602

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    120/299      2.97G    0.01565    0.01189   0.003869         34        640: 100% 12/12 [00:02<00:00,  4.50it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.04it/s]
                   all         26         26      0.737      0.828      0.772      0.552

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    121/299      2.97G     0.0151    0.01152   0.002405         27        640: 100% 12/12 [00:02<00:00,  5.83it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.39it/s]
                   all         26         26      0.742      0.873      0.805      0.571

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    122/299      2.97G    0.01843    0.01183   0.004055         32        640: 100% 12/12 [00:02<00:00,  5.98it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.79it/s]
                   all         26         26      0.739       0.86        0.8      0.589

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    123/299      2.97G    0.02117    0.01061   0.002153         28        640: 100% 12/12 [00:01<00:00,  6.01it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.26it/s]
                   all         26         26       0.74      0.866      0.814      0.541

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    124/299      2.97G    0.01611    0.01192   0.003968         36        640: 100% 12/12 [00:01<00:00,  6.14it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.35it/s]
                   all         26         26      0.763      0.814      0.812       0.59

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    125/299      2.97G    0.01746    0.01062   0.002254         28        640: 100% 12/12 [00:01<00:00,  6.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.29it/s]
                   all         26         26      0.772      0.767      0.799      0.532

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    126/299      2.97G    0.01909    0.01125   0.002848         33        640: 100% 12/12 [00:01<00:00,  6.02it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.46it/s]
                   all         26         26      0.754      0.756      0.778       0.51

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    127/299      2.97G    0.01726    0.01129   0.005197         27        640: 100% 12/12 [00:01<00:00,  6.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.72it/s]
                   all         26         26      0.732      0.719      0.733      0.492

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    128/299      2.97G    0.01582     0.0115   0.003884         32        640: 100% 12/12 [00:01<00:00,  6.00it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.82it/s]
                   all         26         26      0.745      0.725      0.727      0.475

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    129/299      2.97G    0.02111     0.0113   0.005916         27        640: 100% 12/12 [00:01<00:00,  6.14it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.66it/s]
                   all         26         26      0.733      0.784      0.737      0.526

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    130/299      2.97G    0.01839    0.01069   0.002895         28        640: 100% 12/12 [00:01<00:00,  6.10it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.57it/s]
                   all         26         26      0.718      0.794      0.758       0.51

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    131/299      2.97G     0.0155   0.009704   0.003222         29        640: 100% 12/12 [00:01<00:00,  6.15it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.65it/s]
                   all         26         26      0.716      0.743      0.769      0.568

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    132/299      2.97G    0.02196    0.01173   0.006625         23        640: 100% 12/12 [00:01<00:00,  6.08it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.87it/s]
                   all         26         26      0.738      0.876      0.795      0.482

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    133/299      2.97G    0.01614     0.0105   0.005006         24        640: 100% 12/12 [00:01<00:00,  6.11it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.60it/s]
                   all         26         26      0.751      0.927      0.811      0.549

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    134/299      2.97G    0.01426    0.01129   0.002081         29        640: 100% 12/12 [00:02<00:00,  5.93it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.07it/s]
                   all         26         26      0.817      0.854      0.828       0.54

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    135/299      2.97G    0.02194     0.0103    0.00226         19        640: 100% 12/12 [00:02<00:00,  5.77it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.63it/s]
                   all         26         26      0.804       0.82        0.8       0.56

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    136/299      2.97G    0.01999    0.01095   0.003652         28        640: 100% 12/12 [00:01<00:00,  6.05it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.25it/s]
                   all         26         26      0.804      0.939      0.848       0.56

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    137/299      2.97G    0.01423    0.01033    0.00253         25        640: 100% 12/12 [00:01<00:00,  6.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.49it/s]
                   all         26         26       0.78      0.879      0.827      0.528

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    138/299      2.97G     0.0192    0.01094   0.003129         23        640: 100% 12/12 [00:02<00:00,  5.95it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.19it/s]
                   all         26         26      0.744      0.888      0.812      0.527

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    139/299      2.97G    0.01448    0.01118   0.002097         31        640: 100% 12/12 [00:02<00:00,  5.98it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.81it/s]
                   all         26         26      0.758      0.863      0.793      0.465

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    140/299      2.97G    0.02294    0.01142   0.005009         24        640: 100% 12/12 [00:01<00:00,  6.00it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.23it/s]
                   all         26         26      0.694      0.836      0.766      0.562

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    141/299      2.97G    0.02098    0.01243   0.004266         37        640: 100% 12/12 [00:01<00:00,  6.00it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.71it/s]
                   all         26         26       0.74      0.807      0.783      0.516

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    142/299      2.97G    0.01658    0.01133   0.003336         34        640: 100% 12/12 [00:03<00:00,  3.86it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  4.55it/s]
                   all         26         26      0.807      0.889       0.81      0.526

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    143/299      2.97G    0.01517    0.01006   0.004005         23        640: 100% 12/12 [00:03<00:00,  3.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  4.83it/s]
                   all         26         26      0.808      0.874      0.826      0.549

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    144/299      2.97G    0.01573    0.01115   0.003629         28        640: 100% 12/12 [00:03<00:00,  3.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  6.20it/s]
                   all         26         26      0.782      0.827      0.812      0.553

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    145/299      2.97G    0.01613    0.01171   0.002402         29        640: 100% 12/12 [00:02<00:00,  5.97it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.67it/s]
                   all         26         26      0.703      0.805      0.783      0.562

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    146/299      2.97G    0.01508    0.01115   0.002789         29        640: 100% 12/12 [00:01<00:00,  6.22it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.60it/s]
                   all         26         26      0.745      0.825      0.759      0.511

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    147/299      2.97G    0.02015    0.01107   0.007034         30        640: 100% 12/12 [00:01<00:00,  6.10it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.43it/s]
                   all         26         26      0.694      0.796      0.746      0.585

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    148/299      2.97G    0.01744    0.01059   0.002813         24        640: 100% 12/12 [00:02<00:00,  5.94it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.54it/s]
                   all         26         26      0.691      0.745      0.732      0.583

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    149/299      2.97G     0.0179    0.01094   0.002766         26        640: 100% 12/12 [00:02<00:00,  5.87it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:01<00:00,  1.13it/s]
                   all         26         26      0.694      0.778      0.779      0.531

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    150/299      2.97G    0.01762    0.01043   0.002687         34        640: 100% 12/12 [00:02<00:00,  5.18it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.16it/s]
                   all         26         26      0.723      0.793      0.773       0.53

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    151/299      2.97G    0.01348    0.01052   0.002847         23        640: 100% 12/12 [00:01<00:00,  6.04it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.65it/s]
                   all         26         26      0.689       0.87      0.798      0.502

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    152/299      2.97G    0.02163    0.01048   0.007703         31        640: 100% 12/12 [00:01<00:00,  6.01it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.48it/s]
                   all         26         26      0.743      0.832      0.783      0.527

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    153/299      2.97G    0.01412    0.01074   0.002962         28        640: 100% 12/12 [00:01<00:00,  6.13it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.14it/s]
                   all         26         26      0.678      0.771      0.786      0.521

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    154/299      2.97G    0.01676    0.01111   0.002489         32        640: 100% 12/12 [00:02<00:00,  5.90it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.90it/s]
                   all         26         26      0.684      0.807      0.776      0.509

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    155/299      2.97G    0.01578     0.0115   0.002006         26        640: 100% 12/12 [00:01<00:00,  6.06it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.98it/s]
                   all         26         26       0.64      0.884      0.772      0.522

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    156/299      2.97G    0.01402    0.01145    0.00187         29        640: 100% 12/12 [00:01<00:00,  6.06it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.80it/s]
                   all         26         26      0.653      0.837       0.78      0.566

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    157/299      2.97G    0.01595    0.01146   0.003216         34        640: 100% 12/12 [00:01<00:00,  6.04it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  9.16it/s]
                   all         26         26       0.68       0.71      0.756      0.509

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    158/299      2.97G    0.01457    0.01098   0.003136         31        640: 100% 12/12 [00:01<00:00,  6.12it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.73it/s]
                   all         26         26      0.749      0.715      0.768      0.546

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    159/299      2.97G    0.01816    0.01152   0.003155         37        640: 100% 12/12 [00:01<00:00,  6.01it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.69it/s]
                   all         26         26       0.73      0.709       0.76      0.534

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    160/299      2.97G    0.01357   0.009558   0.003583         25        640: 100% 12/12 [00:02<00:00,  5.94it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.49it/s]
                   all         26         26      0.671      0.782      0.736      0.477

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    161/299      2.97G     0.0146    0.01143   0.002545         30        640: 100% 12/12 [00:01<00:00,  6.08it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.81it/s]
                   all         26         26       0.64       0.83      0.736      0.534

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    162/299      2.97G     0.0154    0.01067   0.002518         30        640: 100% 12/12 [00:01<00:00,  6.14it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.66it/s]
                   all         26         26       0.65      0.814      0.727       0.48

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    163/299      2.97G    0.01692    0.01027   0.004334         27        640: 100% 12/12 [00:02<00:00,  5.99it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  8.53it/s]
                   all         26         26      0.703      0.762       0.74      0.518

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    164/299      2.97G    0.01768    0.01022   0.002528         30        640: 100% 12/12 [00:02<00:00,  5.95it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  7.94it/s]
                   all         26         26      0.628      0.841      0.738      0.524
Stopping training early as no improvement observed in last 100 epochs. Best results observed at epoch 64, best model saved as best.pt.
To update EarlyStopping(patience=100) pass a new patience value, i.e. `python train.py --patience 300` or use `--patience 0` to disable EarlyStopping.

165 epochs completed in 0.129 hours.
Optimizer stripped from runs/train/exp2/weights/last.pt, 14.4MB
Optimizer stripped from runs/train/exp2/weights/best.pt, 14.4MB

Validating runs/train/exp2/weights/best.pt...
Fusing layers... 
Model summary: 157 layers, 7020913 parameters, 0 gradients, 15.8 GFLOPs
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 2/2 [00:00<00:00,  4.77it/s]
                   all         26         26      0.797      0.893      0.883        0.6
               abacaxi         26          9      0.997          1      0.995      0.778
                banana         26          5      0.945          1      0.995      0.673
              melancia         26          5      0.886          1      0.995      0.611
                  pera         26          7      0.362      0.571      0.546      0.339
Results saved to runs/train/exp2
wandb: Waiting for W&B process to finish... (success).
wandb: 
wandb: Run history:
wandb:      metrics/mAP_0.5 ▁▄▄▆▆▅▅▆▇▆▆▆▇▇▇█▇▇█▇▇▇▇▇▇▇█▇▇▇▇▇▇▇▇▇▇▇▇█
wandb: metrics/mAP_0.5:0.95 ▁▃▄▄▅▄▅▅▅▆▅▅▇▆▆█▆▇▇▇▇▆▇▇▇▇▇▆██▇█▇▆▇█▇▇▇█
wandb:    metrics/precision ▁▆█▇▅▄▅▆▆▆▇▆▇▇▆▇▆▇▇▇▆▇▆▇▇▆▇▇▆▇▇▆▇▇▇▆▆▆▇▇
wandb:       metrics/recall █▂▁▃▅▃▆▇▆▆▅▆▅▇▇▇█▆▇▇▇▅▆▅▆▆▇▆▇▇▆▆▇▇▇▆▇▇▅▇
wandb:       train/box_loss █▅▅▄▄▃▃▂▃▂▃▃▂▂▂▂▂▂▂▂▃▂▂▂▁▁▂▁▁▁▁▂▁▁▂▁▂▁▁▁
wandb:       train/cls_loss █▆▅▅▅▄▃▃▂▂▂▂▂▂▂▂▁▂▂▂▁▂▁▁▁▂▁▁▁▁▁▂▂▁▁▁▁▁▁▁
wandb:       train/obj_loss █▅▃▃▃▃▂▃▂▂▂▂▂▂▂▂▂▂▂▂▂▂▂▁▁▁▁▂▂▁▁▁▁▁▂▁▁▁▁▁
wandb:         val/box_loss ▇█▆▆▄▃▅▄▇▃▃▂▂▄▃▁▁▁▂▂▁▃▃▁▂▂▂▃▂▂▁▂▂▂▁▁▂▂▁▁
wandb:         val/cls_loss █▅▅▄▄▃▂▂▂▂▂▁▁▁▁▁▁▂▂▁▂▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▂▁
wandb:         val/obj_loss █▃▂▁▁▂▁▁▁▂▂▁▁▁▁▁▁▁▁▁▁▁▁▂▁▁▁▁▁▂▂▂▁▁▁▁▁▁▁▁
wandb:                x/lr0 █▄▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
wandb:                x/lr1 ▁▅█████▇▇▇▇▇▇▇▆▆▆▆▆▆▆▆▅▅▅▅▅▅▅▅▄▄▄▄▄▄▄▄▃▃
wandb:                x/lr2 ▁▅█████▇▇▇▇▇▇▇▆▆▆▆▆▆▆▆▅▅▅▅▅▅▅▅▄▄▄▄▄▄▄▄▃▃
wandb: 
wandb: Run summary:
wandb:           best/epoch 64
wandb:         best/mAP_0.5 0.88169
wandb:    best/mAP_0.5:0.95 0.60056
wandb:       best/precision 0.79762
wandb:          best/recall 0.89286
wandb:      metrics/mAP_0.5 0.88267
wandb: metrics/mAP_0.5:0.95 0.6003
wandb:    metrics/precision 0.79734
wandb:       metrics/recall 0.89286
wandb:       train/box_loss 0.01768
wandb:       train/cls_loss 0.00253
wandb:       train/obj_loss 0.01022
wandb:         val/box_loss 0.01342
wandb:         val/cls_loss 0.00103
wandb:         val/obj_loss 0.00408
wandb:                x/lr0 0.00462
wandb:                x/lr1 0.00462
wandb:                x/lr2 0.00462
  ```
</details>

### Evidências do treinamento

https://wandb.ai/alysonlaurentino/YOLOv5/runs/301ma730

## Roboflow

Nessa seção deve colocar o link para acessar o dataset no Roboflow

Exemplo de link: [FrutasOf](https://app.roboflow.com/ds/COcmyBus3h?key=gUHN8cwOPH)
ou
https://app.roboflow.com/cesar-oayyo/frutasof/3

## HuggingFace

Nessa seção você deve publicar o link para o HuggingFace