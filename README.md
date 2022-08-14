# Projeto Final - Modelos Preditivos Conexionistas

### Carlos Fernando R. Sinésio

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|Classificação de Imagens<br>|YOLOv5|PyTorch|

## Performance

O modelo treinado possui performance de **77,7%**.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```text
A saída de streaming foi truncada nas últimas 5000 linhas.
  426/7999     12.1G   0.02507  0.007992   0.02062       249       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.709      0.437      0.585      0.436

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  427/7999     12.1G    0.0262  0.008795   0.02061       268       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.724      0.388      0.603      0.422

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  428/7999     12.1G   0.02608  0.009668   0.01762       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.733      0.387      0.591      0.427

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  429/7999     12.1G   0.02717  0.008353   0.02041       276       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.454      0.665      0.576      0.406

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  430/7999     12.1G   0.02563  0.009273   0.02076       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.458      0.615      0.542      0.393

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  431/7999     12.1G   0.02769  0.009489   0.02089       296       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130       0.48       0.62      0.508      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  432/7999     12.1G   0.02449  0.009087   0.01964       298       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.431      0.461      0.474      0.337

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  433/7999     12.1G   0.02626  0.008148   0.01765       279       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.455      0.466       0.47      0.321

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  434/7999     12.1G   0.02354   0.00917   0.02118       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.478      0.454      0.486      0.349

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  435/7999     12.1G   0.02507  0.008587   0.02172       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.731      0.272      0.447      0.318

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  436/7999     12.1G   0.02786  0.008265   0.02374       270       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.30it/s]
                 all        101        130      0.754      0.264       0.43      0.312

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  437/7999     12.1G   0.02576  0.009268   0.01961       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.585      0.337      0.449      0.317

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  438/7999     12.1G   0.02725  0.008611   0.02038       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.613      0.396      0.486      0.352

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  439/7999     12.1G   0.02612  0.009128   0.01864       294       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.596      0.374      0.461      0.325

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  440/7999     12.1G   0.02649  0.009497   0.01611       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.672      0.378      0.479      0.337

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  441/7999     12.1G   0.02562  0.008778   0.01493       297       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.627      0.395       0.48      0.342

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  442/7999     12.1G   0.02651  0.009656   0.01751       309       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.72      0.378       0.54      0.389

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  443/7999     12.1G   0.02626   0.01017   0.01891       309       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.659       0.36      0.516      0.366

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  444/7999     12.1G   0.02599  0.008606   0.02076       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.482      0.381      0.485      0.357

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  445/7999     12.1G   0.02593   0.00947   0.01871       291       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.676      0.315      0.492      0.353

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  446/7999     12.1G   0.02621  0.009461   0.01785       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.528      0.501      0.539      0.404

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  447/7999     12.1G   0.02445   0.00822   0.02121       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130       0.53      0.519      0.546      0.392

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  448/7999     12.1G   0.02621  0.008909   0.01762       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.591      0.417       0.55      0.408

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  449/7999     12.1G   0.02569  0.008385    0.0232       266       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.731      0.361       0.56      0.392

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  450/7999     12.1G   0.02571  0.009505     0.019       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.835      0.344      0.591      0.425

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  451/7999     12.1G   0.02714  0.009243   0.02005       289       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.845      0.341      0.585      0.406

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  452/7999     12.1G   0.02914  0.009032   0.01874       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.689      0.399      0.596      0.448

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  453/7999     12.1G   0.02836  0.009703   0.02035       303       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.386      0.663      0.587      0.431

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  454/7999     12.1G   0.02269   0.00812   0.01904       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.398      0.684      0.591      0.442

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  455/7999     12.1G   0.02592   0.00829   0.01817       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.389      0.661      0.589      0.419

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  456/7999     12.1G     0.025  0.009669   0.01755       331       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.375      0.621      0.564      0.399

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  457/7999     12.1G   0.02746   0.00926   0.01901       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.391      0.607      0.553      0.391

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  458/7999     12.1G   0.02285  0.008242    0.0198       266       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.394      0.514      0.579      0.419

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  459/7999     12.1G   0.02434  0.008838   0.01927       302       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.427      0.457      0.554      0.372

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  460/7999     12.1G   0.02464  0.009015   0.02067       304       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.262      0.853      0.473       0.32

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  461/7999     12.1G   0.02659  0.009164   0.02237       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.30it/s]
                 all        101        130      0.544      0.321      0.444      0.315

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  462/7999     12.1G   0.02356  0.008839   0.01978       289       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.402      0.428      0.455      0.325

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  463/7999     12.1G   0.02727   0.00935   0.01679       295       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.434      0.526      0.482      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  464/7999     12.1G   0.02529  0.008689   0.01996       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.438      0.589      0.498      0.359

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  465/7999     12.1G   0.02525  0.008689   0.01847       270       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.629      0.436       0.49      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  466/7999     12.1G   0.02473  0.008653    0.0158       293       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.694      0.419      0.494      0.357

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  467/7999     12.1G    0.0275   0.01037   0.02058       313       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.621      0.438      0.488      0.356

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  468/7999     12.1G   0.02261  0.007811    0.0227       251       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.693      0.345      0.457      0.324

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  469/7999     12.1G   0.02566  0.008263    0.0172       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.685      0.401      0.477      0.329

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  470/7999     12.1G   0.02639  0.009155   0.01917       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.602      0.408      0.462      0.322

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  471/7999     12.1G   0.02581  0.008939   0.01998       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.747      0.387      0.491      0.349

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  472/7999     12.1G   0.02832  0.009702   0.01848       299       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.747      0.406      0.564      0.406

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  473/7999     12.1G   0.02621  0.008824   0.02204       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.66      0.393      0.552      0.407

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  474/7999     12.1G   0.02563  0.009464   0.01955       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.695      0.384       0.53      0.378

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  475/7999     12.1G   0.02631  0.008137    0.0213       260       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.673      0.371      0.486      0.368

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  476/7999     12.1G   0.02437  0.008387    0.0173       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.638      0.389      0.461      0.336

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  477/7999     12.1G   0.02801    0.0103   0.01841       297       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.668       0.39      0.446      0.331

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  478/7999     12.1G   0.02598  0.008771   0.02022       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130      0.633      0.373      0.429      0.306

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  479/7999     12.1G   0.02815  0.008429   0.02188       275       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.654      0.389      0.425      0.319

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  480/7999     12.1G   0.02866  0.009289   0.01998       296       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130      0.645      0.373      0.451      0.313

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  481/7999     12.1G   0.02497  0.008707   0.01972       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.30it/s]
                 all        101        130      0.561      0.403      0.455      0.343

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  482/7999     12.1G   0.02963  0.009309   0.01398       292       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.527       0.41      0.458      0.322

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  483/7999     12.1G   0.02591  0.008585   0.02014       261       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.577      0.412      0.469      0.357

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  484/7999     12.1G   0.02307  0.008583   0.01709       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.615      0.409      0.502      0.363

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  485/7999     12.1G   0.02655  0.008049    0.0167       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.596      0.434      0.535      0.399

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  486/7999     12.1G   0.02498  0.008264   0.02018       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.742      0.327      0.544      0.401

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  487/7999     12.1G   0.02388  0.008717   0.01976       277       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.708      0.331      0.517      0.394

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  488/7999     12.1G   0.02573  0.008043   0.01824       254       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.71      0.339       0.49      0.371

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  489/7999     12.1G   0.02492  0.009265   0.01588       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.518      0.431      0.463       0.35

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  490/7999     12.1G   0.02545  0.008168   0.02138       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.483      0.429      0.458      0.349

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  491/7999     12.1G   0.02464  0.008447   0.01793       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.479      0.437      0.475      0.355

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  492/7999     12.1G   0.02665  0.008931    0.0228       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.526      0.419      0.472      0.345

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  493/7999     12.1G    0.0245  0.008652   0.01951       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.418      0.514      0.494      0.358

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  494/7999     12.1G   0.02561  0.009206    0.0198       300       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.379      0.593      0.516      0.372

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  495/7999     12.1G   0.02627  0.009378   0.01708       296       320: 100% 1/1 [00:01<00:00,  1.15s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.398      0.597        0.5      0.367

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  496/7999     12.1G   0.02625   0.00915   0.01908       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.386      0.559      0.495      0.368

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  497/7999     12.1G   0.02292  0.007544   0.01533       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.426      0.629      0.533      0.378

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  498/7999     12.1G   0.02608  0.008428   0.01787       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.444      0.648      0.569      0.407

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  499/7999     12.1G   0.02517  0.007342   0.02141       225       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.582      0.381      0.538      0.407

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  500/7999     12.1G   0.02457  0.007927   0.02387       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.463      0.488      0.515      0.382

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  501/7999     12.1G   0.02448  0.007834   0.02028       266       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.413      0.425      0.482      0.356

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  502/7999     12.1G   0.02469  0.007778   0.01684       277       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.219      0.865      0.483      0.347

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  503/7999     12.1G    0.0259  0.008536   0.01832       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.205      0.879       0.46       0.34

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  504/7999     12.1G   0.02562  0.008125   0.01901       268       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.201      0.899      0.472      0.328

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  505/7999     12.1G   0.02571  0.008589    0.0193       274       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.187      0.918      0.474      0.343

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  506/7999     12.1G   0.02434  0.008573   0.01962       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.869      0.266      0.502      0.359

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  507/7999     12.1G   0.02412  0.008804   0.01635       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.839      0.255      0.517      0.373

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  508/7999     12.1G   0.02647  0.008748   0.01668       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.679      0.331      0.526      0.362

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  509/7999     12.1G   0.02421  0.009044   0.01886       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.722      0.288       0.53      0.358

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  510/7999     12.1G   0.02405  0.008747   0.02075       282       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130       0.74      0.324       0.54      0.362

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  511/7999     12.1G   0.02625  0.009378   0.01667       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130       0.66       0.38      0.503      0.355

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  512/7999     12.1G   0.02725   0.00883   0.01658       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.586      0.421      0.472      0.326

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  513/7999     12.1G   0.02662  0.008902   0.01747       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130       0.59      0.406      0.446      0.322

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  514/7999     12.1G   0.02511  0.008664   0.02065       286       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.603      0.329      0.421      0.293

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  515/7999     12.1G   0.02408  0.008105    0.0234       267       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.625       0.37      0.454      0.339

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  516/7999     12.1G   0.02406   0.00927   0.01615       301       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.629      0.374      0.458      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  517/7999     12.1G    0.0247  0.009595   0.01906       302       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.583      0.365      0.421      0.314

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  518/7999     12.1G   0.02484  0.009289   0.01643       310       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.629      0.353      0.537      0.391

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  519/7999     12.1G    0.0271  0.008737   0.02072       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.238      0.917      0.546      0.413

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  520/7999     12.1G   0.02337  0.008655   0.01863       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.22      0.901      0.476      0.334

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  521/7999     12.1G   0.02603  0.008957   0.01864       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.236       0.87      0.457      0.336

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  522/7999     12.1G   0.02675  0.008325   0.01896       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.629      0.359      0.477      0.339

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  523/7999     12.1G   0.02768  0.008223   0.01854       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.651      0.381      0.498      0.365

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  524/7999     12.1G    0.0256   0.00971   0.01632       314       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130       0.68       0.38      0.503       0.35

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  525/7999     12.1G    0.0261  0.008313   0.01756       294       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.67      0.402      0.495       0.35

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  526/7999     12.1G   0.02541  0.008323    0.0196       270       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.612      0.403       0.45      0.309

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  527/7999     12.1G   0.02459  0.007825   0.01817       260       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.218      0.744      0.343       0.23

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  528/7999     12.1G   0.02836  0.009324    0.0204       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.203      0.674       0.31      0.212

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  529/7999     12.1G    0.0254  0.008302   0.02176       253       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130        0.2      0.645      0.284      0.199

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  530/7999     12.1G   0.02442   0.00823   0.01893       270       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.618      0.162      0.253       0.17

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  531/7999     12.1G   0.02555  0.007868   0.01936       268       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.32it/s]
                 all        101        130      0.362      0.194      0.232      0.155

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  532/7999     12.1G    0.0267  0.007979   0.01922       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.456      0.216      0.233      0.165

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  533/7999     12.1G   0.02733  0.009268   0.01745       293       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all        101        130       0.44      0.212      0.244      0.177

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  534/7999     12.1G   0.02441  0.007728    0.0204       256       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130      0.446      0.227      0.251      0.181

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  535/7999     12.1G   0.02498  0.008664   0.02098       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130      0.412      0.234      0.297      0.213

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  536/7999     12.1G   0.02473  0.007907   0.01917       270       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.30it/s]
                 all        101        130      0.424       0.29      0.312      0.226

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  537/7999     12.1G   0.02449  0.008599   0.01827       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130      0.548      0.325      0.329       0.23

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  538/7999     12.1G   0.02551   0.00899   0.02074       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all        101        130      0.529      0.388      0.329      0.234

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  539/7999     12.1G   0.02511  0.008869    0.0171       305       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.592       0.37      0.354      0.252

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  540/7999     12.1G   0.02546  0.008282   0.02137       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.645      0.348      0.371      0.264

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  541/7999     12.1G   0.02329  0.008711   0.01907       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.627       0.37      0.416        0.3

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  542/7999     12.1G   0.02533  0.007862    0.0192       280       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.649      0.359      0.483      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  543/7999     12.1G   0.02611  0.009142   0.01836       293       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.628      0.359      0.467      0.347

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  544/7999     12.1G   0.02609  0.008275    0.0191       274       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.669       0.34      0.499      0.356

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  545/7999     12.1G    0.0265  0.009546   0.01999       300       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.688      0.285      0.509       0.38

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  546/7999     12.1G   0.02166  0.008362   0.02042       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.278      0.603      0.487      0.358

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  547/7999     12.1G   0.02551  0.008985   0.01883       291       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.638      0.302      0.477      0.365

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  548/7999     12.1G   0.02513  0.008608   0.01976       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.198      0.909      0.467      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  549/7999     12.1G   0.02396  0.007778   0.02005       259       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.269      0.635      0.437      0.329

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  550/7999     12.1G   0.02534  0.008162   0.01696       282       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.387      0.542      0.422      0.294

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  551/7999     12.1G   0.02647  0.007935   0.02214       257       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.315       0.78      0.424      0.317

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  552/7999     12.1G   0.02451  0.008243   0.02204       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130       0.31      0.472      0.401      0.283

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  553/7999     12.1G    0.0248  0.008272   0.01762       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130       0.44      0.369      0.386      0.285

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  554/7999     12.1G   0.02591  0.008458   0.01632       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all        101        130      0.429      0.379      0.366      0.253

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  555/7999     12.1G   0.02503  0.007757   0.02134       242       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.385      0.359      0.361      0.267

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  556/7999     12.1G   0.02549  0.009221   0.01994       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.443      0.341      0.331      0.244

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  557/7999     12.1G    0.0245  0.008649   0.02022       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all        101        130      0.481      0.373      0.309      0.228

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  558/7999     12.1G   0.02476  0.008089     0.022       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.601      0.397      0.353      0.253

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  559/7999     12.1G   0.02393  0.007635   0.01868       267       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.622      0.371      0.363      0.271

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  560/7999     12.1G   0.02776  0.009171   0.02153       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.634      0.413      0.369      0.279

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  561/7999     12.1G   0.02335  0.009348   0.01741       294       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.644      0.402      0.408      0.308

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  562/7999     12.1G   0.02453   0.00866   0.01479       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.655       0.38      0.445      0.316

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  563/7999     12.1G   0.02278  0.007332   0.01542       248       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.668      0.402      0.466      0.347

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  564/7999     12.1G   0.02727  0.009126   0.01781       304       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.668      0.399       0.49       0.34

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  565/7999     12.1G    0.0247  0.008049   0.02086       266       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.676      0.349      0.456      0.328

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  566/7999     12.1G   0.02463  0.008073   0.01927       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all        101        130       0.66       0.37      0.431      0.297

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  567/7999     12.1G   0.02814  0.008809    0.0191       269       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.655      0.349       0.41      0.299

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  568/7999     12.1G   0.02614  0.009285   0.01773       269       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.676      0.403      0.421      0.302

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  569/7999     12.1G   0.02334  0.007998   0.01621       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.679      0.382      0.447       0.33

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  570/7999     12.1G   0.02676  0.008594   0.01909       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.698      0.382      0.451      0.321

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  571/7999     12.1G   0.02252  0.009054   0.01878       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.668      0.386      0.479      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  572/7999     12.1G   0.02554  0.009394   0.02112       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.651      0.371      0.513      0.338

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  573/7999     12.1G   0.02434  0.008069   0.01914       266       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.336      0.522      0.551      0.395

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  574/7999     12.1G   0.02526  0.008817   0.01767       297       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.78      0.286      0.502      0.359

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  575/7999     12.1G   0.02542  0.008741   0.01714       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.14it/s]
                 all        101        130      0.772      0.276      0.477       0.35

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  576/7999     12.1G   0.02922   0.00859   0.01842       294       320: 100% 1/1 [00:01<00:00,  1.20s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.768      0.276      0.464      0.328

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  577/7999     12.1G   0.02545  0.009337   0.01951       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.338      0.501      0.494      0.356

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  578/7999     12.1G    0.0264  0.008397   0.01965       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.372      0.631       0.54      0.397

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  579/7999     12.1G    0.0251  0.007902   0.01822       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.386      0.632      0.536      0.375

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  580/7999     12.1G   0.02468  0.009008   0.02054       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.379      0.627      0.515      0.362

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  581/7999     12.1G   0.02373  0.008874   0.01665       311       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.372      0.554      0.522      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  582/7999     12.1G   0.02475  0.008872   0.02104       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.375      0.533      0.504      0.342

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  583/7999     12.1G   0.02249  0.007529   0.01874       260       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.373      0.534      0.485       0.33

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  584/7999     12.1G   0.02558  0.008393   0.02042       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.394      0.563        0.5      0.346

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  585/7999     12.1G   0.02409  0.009292    0.0164       313       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.394      0.563      0.495      0.331

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  586/7999     12.1G   0.02678  0.008704    0.0197       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130       0.37      0.506      0.472      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  587/7999     12.1G   0.02547  0.008306   0.01945       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.35      0.469      0.464      0.314

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  588/7999     12.1G    0.0257  0.008753   0.01953       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.405      0.485      0.502      0.348

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  589/7999     12.1G   0.02654  0.008625   0.01732       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.448      0.578      0.559       0.37

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  590/7999     12.1G    0.0269  0.008906   0.01809       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.457      0.575      0.552      0.375

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  591/7999     12.1G   0.02385  0.007758   0.01851       272       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.439      0.577      0.569      0.375

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  592/7999     12.1G   0.02644  0.008395   0.01894       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.454      0.486      0.547      0.373

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  593/7999     12.1G    0.0262  0.008867   0.01863       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.505      0.642      0.569      0.382

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  594/7999     12.1G   0.02286  0.007733   0.01751       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.535       0.76      0.673      0.462

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  595/7999     12.1G   0.02506     0.009   0.02037       289       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.555      0.775      0.711      0.472

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  596/7999     12.1G   0.02379  0.008541   0.02056       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:01<00:00,  1.03s/it]
                 all        101        130      0.544       0.82      0.717      0.451

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  597/7999     12.1G   0.02558  0.008556   0.01724       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.582      0.787      0.753       0.48

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  598/7999     12.1G   0.02507  0.009113   0.02045       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.599      0.822      0.779      0.493

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  599/7999     12.1G   0.02507  0.008931   0.02032       268       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.607      0.799      0.754      0.477

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  600/7999     12.1G   0.02553  0.008573   0.01905       289       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.579      0.794      0.749      0.504

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  601/7999     12.1G   0.02447  0.007682   0.01967       268       320: 100% 1/1 [00:01<00:00,  1.36s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.516      0.802      0.715      0.478

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  602/7999     12.1G   0.02574  0.009178   0.01682       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130       0.52      0.803      0.718      0.485

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  603/7999     12.1G   0.02547   0.00835   0.01612       294       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.499      0.787      0.682      0.451

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  604/7999     12.1G   0.02597  0.009278   0.01807       297       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.14it/s]
                 all        101        130      0.634        0.6      0.642      0.447

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  605/7999     12.1G    0.0237  0.008098   0.01988       271       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.14it/s]
                 all        101        130      0.465      0.711      0.606      0.404

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  606/7999     12.1G   0.02703  0.009481   0.01921       292       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.615       0.49      0.613      0.425

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  607/7999     12.1G   0.02463  0.008514   0.01926       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.621      0.482      0.639      0.443

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  608/7999     12.1G   0.02269  0.009042   0.02114       296       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.572      0.616      0.659      0.468

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  609/7999     12.1G   0.02331  0.007973   0.02088       248       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.721       0.49      0.664      0.469

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  610/7999     12.1G   0.02279  0.008258   0.01999       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.759      0.517       0.68      0.498

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  611/7999     12.1G   0.02687  0.009439   0.01763       308       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.712      0.467      0.708      0.503

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  612/7999     12.1G   0.02691  0.009732   0.01969       307       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.726      0.565      0.747      0.522

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  613/7999     12.1G   0.02434  0.008252   0.02099       255       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130       0.71      0.545      0.764      0.533

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  614/7999     12.1G    0.0265  0.008995      0.02       289       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.757      0.537      0.777      0.573

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  615/7999     12.1G   0.02716  0.008521    0.0192       291       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.685      0.592      0.731      0.543

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  616/7999     12.1G   0.02287  0.008089   0.01845       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.713      0.437      0.665      0.482

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  617/7999     12.1G   0.02645  0.008533   0.01977       268       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.616      0.477      0.639      0.464

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  618/7999     12.1G   0.02504  0.008663   0.02008       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.509       0.42      0.547      0.417

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  619/7999     12.1G   0.02742  0.009551   0.01868       308       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.554      0.421      0.557      0.403

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  620/7999     12.1G   0.02416  0.009244   0.01645       330       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.461      0.652      0.566      0.425

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  621/7999     12.1G   0.02746  0.009256   0.01717       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.598      0.547      0.583       0.43

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  622/7999     12.1G   0.02476  0.008903   0.02025       269       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130       0.64      0.535      0.676        0.5

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  623/7999     12.1G   0.02384  0.008612   0.01822       275       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.637      0.572      0.705      0.517

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  624/7999     12.1G   0.02473  0.007808   0.01895       252       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.673      0.581      0.728      0.516

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  625/7999     12.1G   0.02298  0.007882   0.01762       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.682      0.608      0.736      0.507

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  626/7999     12.1G    0.0262  0.008416   0.01691       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.704      0.602      0.746      0.509

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  627/7999     12.1G   0.02329  0.008141   0.01788       277       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.683      0.552      0.714       0.49

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  628/7999     12.1G   0.02337  0.008215   0.01683       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.679      0.598      0.718      0.493

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  629/7999     12.1G   0.02675  0.008897   0.01774       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.717      0.553      0.737      0.504

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  630/7999     12.1G   0.02333  0.008363   0.01996       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.684      0.482      0.705      0.479

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  631/7999     12.1G   0.02598   0.00883   0.02025       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.706      0.495       0.68      0.474

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  632/7999     12.1G   0.02468  0.008035   0.01775       295       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.672      0.433      0.661      0.468

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  633/7999     12.1G   0.02443  0.009735   0.02003       325       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.732      0.404      0.663      0.465

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  634/7999     12.1G   0.02524  0.008026   0.01825       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.79      0.379      0.666       0.48

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  635/7999     12.1G   0.02488  0.008464   0.01815       296       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.13it/s]
                 all        101        130      0.677      0.415      0.657      0.448

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  636/7999     12.1G   0.02415  0.008913   0.01678       319       320: 100% 1/1 [00:01<00:00,  1.19s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.46      0.698      0.663      0.475

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  637/7999     12.1G   0.02492  0.008557   0.01921       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130        0.7      0.394      0.666      0.467

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  638/7999     12.1G   0.02458  0.008622   0.01701       292       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.776      0.393      0.681      0.499

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  639/7999     12.1G   0.02307  0.008846   0.01714       295       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.784      0.389      0.685      0.498

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  640/7999     12.1G   0.02408  0.008901   0.01512       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.471       0.75      0.692      0.524

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  641/7999     12.1G   0.02387  0.008081    0.0187       260       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.463      0.744      0.692      0.506

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  642/7999     12.1G   0.02269  0.008042   0.01974       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.452      0.708       0.67      0.496

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  643/7999     12.1G   0.02319  0.007344   0.01895       240       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.484      0.719      0.644      0.454

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  644/7999     12.1G   0.02501  0.008499   0.01842       292       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.463      0.696       0.63       0.44

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  645/7999     12.1G   0.02319  0.008198   0.01749       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.602      0.466      0.633      0.447

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  646/7999     12.1G   0.02236  0.007748   0.01784       257       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.616      0.501      0.633      0.465

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  647/7999     12.1G   0.02321  0.007252    0.0194       249       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.595      0.512      0.591       0.43

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  648/7999     12.1G   0.02155  0.008088   0.01914       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.607      0.446       0.61      0.434

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  649/7999     12.1G   0.02439  0.007434   0.01917       231       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130        0.8       0.41      0.648      0.448

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  650/7999     12.1G   0.02528  0.008442   0.01721       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.773      0.349       0.62       0.44

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  651/7999     12.1G    0.0232    0.0082   0.01909       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.817      0.341      0.612      0.431

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  652/7999     12.1G   0.02598  0.008461   0.01924       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.768      0.341      0.601      0.427

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  653/7999     12.1G   0.02273  0.008724   0.01696       293       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.757      0.319      0.553      0.386

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  654/7999     12.1G   0.02394  0.008238   0.01953       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.793      0.305      0.533      0.356

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  655/7999     12.1G   0.02444  0.007738   0.01912       275       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.428      0.513      0.539      0.353

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  656/7999     12.1G   0.02242  0.008438   0.01898       289       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130       0.36      0.611      0.469      0.298

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  657/7999     12.1G   0.02454   0.00822   0.02016       269       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.219      0.842       0.47      0.297

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  658/7999     12.1G   0.02086  0.008452   0.01685       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.438      0.538      0.555      0.355

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  659/7999     12.1G   0.02548  0.009464   0.01764       307       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.459      0.575      0.556      0.369

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  660/7999     12.1G   0.02621  0.007845   0.01965       253       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.471      0.574      0.545      0.357

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  661/7999     12.1G   0.02352  0.007715   0.01797       268       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.451      0.546      0.527      0.355

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  662/7999     12.1G   0.02636  0.007837   0.02223       260       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.435      0.548      0.458       0.29

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  663/7999     12.1G   0.02329  0.008328   0.02017       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.421      0.601      0.468        0.3

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  664/7999     12.1G   0.02526  0.009527   0.01673       313       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.421      0.585      0.423      0.254

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  665/7999     12.1G   0.02616  0.008358   0.01843       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.402      0.538       0.41      0.248

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  666/7999     12.1G   0.02293  0.007695   0.01926       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.402      0.523       0.44      0.279

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  667/7999     12.1G   0.02509  0.008718   0.01703       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130       0.38      0.504      0.467      0.305

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  668/7999     12.1G    0.0254  0.008554   0.02126       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.405      0.505      0.463      0.308

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  669/7999     12.1G   0.02459  0.008155   0.01973       248       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.41      0.491      0.471      0.312

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  670/7999     12.1G   0.02408  0.008457   0.01977       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.401      0.511      0.461       0.31

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  671/7999     12.1G   0.02411  0.007964   0.01932       273       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.439      0.554      0.485      0.318

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  672/7999     12.1G   0.02355  0.008295   0.02016       291       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.491      0.654       0.55      0.378

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  673/7999     12.1G    0.0257  0.008283   0.02138       260       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.482      0.663      0.585      0.402

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  674/7999     12.1G   0.02261   0.00803   0.01853       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.477      0.674      0.602      0.427

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  675/7999     12.1G   0.02565  0.009577   0.01539       315       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.482       0.69      0.629       0.42

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  676/7999     12.1G   0.02351  0.008132   0.01815       280       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.488      0.676      0.629      0.431

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  677/7999     12.1G    0.0235  0.007958   0.01806       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.478      0.683      0.606      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  678/7999     12.1G   0.02285  0.008383   0.01678       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.466      0.704       0.62      0.442

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  679/7999     12.1G   0.02702  0.008927   0.01852       299       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.458      0.668      0.608      0.431

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  680/7999     12.1G   0.02359    0.0078   0.01693       265       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.453      0.602      0.592      0.428

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  681/7999     12.1G   0.02457  0.007687   0.02098       267       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.455      0.572      0.587      0.402

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  682/7999     12.1G   0.02585  0.007435   0.02001       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.442      0.568      0.584      0.408

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  683/7999     12.1G   0.02418  0.008667   0.01746       289       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.458      0.579      0.594        0.4

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  684/7999     12.1G   0.02575  0.008301   0.01732       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.467      0.559      0.579      0.406

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  685/7999     12.1G   0.02433  0.008851   0.01664       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.463       0.53      0.539       0.38

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  686/7999     12.1G   0.02478  0.007764   0.01705       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.465      0.491      0.523      0.374

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  687/7999     12.1G   0.02348  0.007659   0.01826       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.463      0.497      0.485      0.345

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  688/7999     12.1G   0.02502   0.00809   0.01836       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.451      0.476      0.451      0.319

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  689/7999     12.1G   0.02805  0.009676    0.0177       308       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.444      0.484      0.467      0.317

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  690/7999     12.1G   0.02252  0.008116   0.01826       269       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.474      0.529      0.524       0.37

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  691/7999     12.1G   0.02355   0.01001    0.0159       337       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.437      0.569      0.529      0.364

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  692/7999     12.1G   0.02696  0.008417   0.01735       273       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.432       0.54      0.497      0.355

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  693/7999     12.1G   0.02428   0.00748   0.01666       255       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.424      0.556      0.478       0.32

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  694/7999     12.1G    0.0228  0.008187   0.02013       280       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.413      0.552      0.471      0.324

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  695/7999     12.1G   0.02608  0.007817   0.02017       268       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.332      0.498      0.447      0.306

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  696/7999     12.1G   0.02372  0.008063   0.01721       269       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.37      0.637       0.45       0.31

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  697/7999     12.1G   0.02554  0.007881   0.02063       260       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.13it/s]
                 all        101        130      0.341      0.611      0.408      0.276

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  698/7999     12.1G   0.02557  0.008992   0.01923       297       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.361      0.654       0.42      0.283

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  699/7999     12.1G   0.02517  0.009261   0.01794       294       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.391      0.658      0.456      0.297

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  700/7999     12.1G   0.02239  0.008435   0.01724       310       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.405      0.605      0.462      0.324

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  701/7999     12.1G    0.0246  0.008723   0.01976       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.395      0.594      0.459      0.318

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  702/7999     12.1G    0.0264  0.008626   0.01621       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.379      0.568      0.442      0.313

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  703/7999     12.1G   0.02232  0.007943   0.01756       295       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130       0.37      0.631       0.43      0.299

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  704/7999     12.1G   0.02545  0.007878   0.01923       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.381      0.574      0.422      0.299

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  705/7999     12.1G   0.02432  0.008321   0.02039       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.368      0.437      0.446      0.311

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  706/7999     12.1G   0.02585   0.00816   0.02114       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.416      0.465      0.449      0.316

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  707/7999     12.1G    0.0228  0.007591   0.02019       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.432      0.445      0.439      0.289

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  708/7999     12.1G   0.02498   0.00904   0.01849       291       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.398      0.471      0.426      0.292

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  709/7999     12.1G   0.02254  0.007955   0.01613       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.383      0.519      0.413      0.261

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  710/7999     12.1G   0.02356  0.008234   0.01629       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.397      0.557       0.42      0.277

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  711/7999     12.1G   0.02511  0.008301   0.01776       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.425      0.576      0.425      0.259

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  712/7999     12.1G   0.02438  0.009046   0.01527       295       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.446      0.578      0.458      0.301

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  713/7999     12.1G   0.02447  0.008823    0.0164       312       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.498      0.563      0.492      0.303

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  714/7999     12.1G   0.02407  0.008284   0.01954       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.447      0.596      0.495      0.326

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  715/7999     12.1G   0.02492  0.007672   0.02157       255       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.44      0.613      0.493      0.321

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  716/7999     12.1G   0.02294  0.008585   0.01855       290       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.447      0.639       0.51      0.343

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  717/7999     12.1G   0.02257  0.009094   0.01605       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.447       0.61      0.507      0.329

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  718/7999     12.1G   0.02375  0.008138   0.01829       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.433      0.612      0.502      0.338

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  719/7999     12.1G   0.02667  0.008525   0.01904       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.43      0.628      0.533      0.358

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  720/7999     12.1G   0.02402  0.009068   0.01845       297       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.409      0.629      0.529      0.348

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  721/7999     12.1G   0.02169  0.007438    0.0159       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.439      0.622      0.541      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  722/7999     12.1G   0.02593  0.008705   0.01904       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.387      0.574      0.515      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  723/7999     12.1G   0.02186  0.008135    0.0152       306       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.404      0.547      0.518      0.349

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  724/7999     12.1G   0.02532  0.009239   0.01883       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.36      0.525       0.48      0.314

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  725/7999     12.1G    0.0232  0.008557   0.01468       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.406      0.523      0.485       0.31

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  726/7999     12.1G    0.0253  0.008913   0.01639       289       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.426      0.607      0.508      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  727/7999     12.1G   0.02354  0.007761   0.01818       264       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.567       0.43      0.531      0.353

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  728/7999     12.1G   0.02238  0.008084   0.02024       286       320: 100% 1/1 [00:01<00:00,  1.19s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.619      0.453      0.556      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  729/7999     12.1G   0.02399  0.008857   0.01677       281       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.628        0.5      0.585      0.387

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  730/7999     12.1G   0.02281  0.008316   0.01942       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130       0.64      0.515      0.597      0.383

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  731/7999     12.1G    0.0228  0.008189   0.01812       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.591      0.486      0.571      0.378

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  732/7999     12.1G   0.02356  0.007595   0.01576       250       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.574      0.483      0.577      0.384

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  733/7999     12.1G   0.02496  0.008524   0.01968       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.567      0.492      0.575      0.388

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  734/7999     12.1G   0.02332   0.00816   0.01979       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.572      0.494      0.602      0.399

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  735/7999     12.1G     0.026  0.007967   0.01805       270       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.58      0.492       0.59      0.395

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  736/7999     12.1G   0.02087  0.007794   0.02299       249       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.623      0.416      0.554      0.367

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  737/7999     12.1G   0.02536   0.00891   0.01743       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.676      0.396      0.562      0.376

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  738/7999     12.1G   0.02293  0.008817   0.01629       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.408       0.68      0.558      0.373

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  739/7999     12.1G    0.0245  0.008298   0.01695       291       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.431      0.603      0.524       0.35

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  740/7999     12.1G   0.02414  0.007905   0.01817       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.606      0.392       0.55       0.36

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  741/7999     12.1G   0.02216  0.007952   0.01909       303       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.611      0.488      0.574      0.364

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  742/7999     12.1G   0.02517  0.008394    0.0176       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.621      0.501      0.632      0.406

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  743/7999     12.1G   0.02095  0.006614   0.01773       237       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.439      0.654      0.592      0.382

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  744/7999     12.1G   0.02464  0.007697   0.01919       253       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.432      0.632      0.578      0.356

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  745/7999     12.1G   0.02401  0.008098    0.0202       272       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.478      0.627       0.57      0.356

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  746/7999     12.1G   0.02516  0.008474   0.01922       269       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.479      0.609      0.588      0.386

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  747/7999     12.1G   0.02325  0.007969   0.01792       277       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.461      0.626      0.584      0.392

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  748/7999     12.1G   0.02411  0.007793    0.0192       258       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.456      0.589      0.571      0.382

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  749/7999     12.1G   0.02671   0.00939    0.0184       302       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.462      0.615      0.571      0.378

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  750/7999     12.1G   0.02493  0.008961      0.02       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.431      0.606      0.576      0.392

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  751/7999     12.1G   0.02282  0.008054   0.01754       260       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.435      0.632      0.575      0.387

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  752/7999     12.1G   0.02436  0.008382   0.01629       299       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.412      0.663      0.582      0.408

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  753/7999     12.1G   0.02359  0.007697   0.01681       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.408      0.652      0.591      0.398

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  754/7999     12.1G   0.02526  0.009047   0.01722       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.449       0.63      0.601      0.414

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  755/7999     12.1G    0.0232  0.008885   0.01865       310       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.465      0.697      0.607      0.415

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  756/7999     12.1G   0.02393  0.008006   0.01759       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.662      0.427      0.596      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  757/7999     12.1G   0.02472  0.008101   0.01881       277       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.679      0.427      0.599       0.41

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  758/7999     12.1G   0.02359  0.007922   0.01725       292       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.13it/s]
                 all        101        130      0.794      0.366      0.589      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  759/7999     12.1G   0.02137  0.008736    0.0197       308       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.699      0.355      0.553      0.373

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  760/7999     12.1G   0.02261  0.007744   0.01721       283       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.466      0.483      0.453      0.305

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  761/7999     12.1G   0.02271  0.007982    0.0188       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.434      0.454      0.387       0.26

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  762/7999     12.1G   0.02346  0.008407   0.01816       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.419      0.424      0.341      0.236

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  763/7999     12.1G   0.02361  0.008011   0.01943       279       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all        101        130      0.389      0.385      0.322       0.21

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  764/7999     12.1G   0.02341  0.008095   0.02151       260       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.413      0.364      0.309      0.188

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  765/7999     12.1G   0.02282  0.008162   0.01753       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130       0.52      0.352      0.303      0.184

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  766/7999     12.1G   0.02341  0.008697   0.01621       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all        101        130      0.405      0.331      0.307      0.182

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  767/7999     12.1G   0.02447  0.008924   0.02205       313       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.539      0.335      0.321      0.203

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  768/7999     12.1G   0.02448  0.008412   0.01836       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130       0.57      0.299      0.358      0.225

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  769/7999     12.1G   0.02481  0.008143   0.01772       268       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.605      0.293      0.406      0.273

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  770/7999     12.1G    0.0246  0.007972   0.02097       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.647      0.286      0.402      0.261

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  771/7999     12.1G   0.02394  0.008525   0.01893       285       320: 100% 1/1 [00:01<00:00,  1.15s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.648      0.352      0.432      0.285

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  772/7999     12.1G   0.02667  0.008999   0.01819       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.635      0.355      0.422      0.279

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  773/7999     12.1G   0.02456  0.007896   0.01819       264       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.655      0.354      0.416      0.272

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  774/7999     12.1G   0.02572  0.008217   0.01815       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130       0.63      0.359      0.453      0.308

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  775/7999     12.1G   0.02501  0.008904   0.02059       281       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.655      0.389      0.565      0.387

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  776/7999     12.1G   0.02382   0.00864   0.01791       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.734      0.384       0.61       0.42

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  777/7999     12.1G   0.02514   0.00809   0.01758       265       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.483        0.7       0.62      0.407

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  778/7999     12.1G   0.02264   0.00812   0.01663       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.516      0.701      0.601       0.41

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  779/7999     12.1G    0.0259  0.008395   0.01994       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.526      0.685      0.566      0.374

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  780/7999     12.1G   0.02471  0.008014   0.02108       251       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130       0.51      0.483      0.471      0.322

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  781/7999     12.1G   0.02162  0.007965   0.01692       265       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.509      0.492      0.431      0.281

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  782/7999     12.1G   0.02587  0.007761   0.01857       254       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.331      0.647      0.448      0.308

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  783/7999     12.1G   0.02255  0.008773   0.01999       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.454      0.587      0.507      0.348

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  784/7999     12.1G   0.02381   0.00784   0.01867       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.484      0.633       0.58        0.4

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  785/7999     12.1G   0.02562  0.008417   0.02072       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.502      0.692      0.601      0.417

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  786/7999     12.1G   0.02378  0.007952   0.01892       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.513      0.696      0.606      0.419

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  787/7999     12.1G   0.02465  0.007636   0.01725       255       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.525      0.711      0.604      0.416

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  788/7999     12.1G   0.02661  0.009665   0.01591       313       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.532      0.722      0.628      0.446

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  789/7999     12.1G   0.02408  0.008327   0.01966       267       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.13it/s]
                 all        101        130      0.516      0.729      0.622      0.437

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  790/7999     12.1G    0.0249  0.008268   0.01979       271       320: 100% 1/1 [00:01<00:00,  1.19s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.513      0.745      0.614      0.419

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  791/7999     12.1G    0.0227  0.008275   0.02168       278       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.481      0.792      0.619      0.415

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  792/7999     12.1G   0.02405  0.008353   0.01763       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.471      0.796       0.63      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  793/7999     12.1G   0.02358  0.008664   0.01793       308       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.476      0.818      0.624      0.412

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  794/7999     12.1G   0.02442  0.007948   0.01589       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.481       0.82      0.612      0.404

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  795/7999     12.1G   0.02414  0.007438   0.01956       264       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.469      0.763      0.598      0.397

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  796/7999     12.1G   0.02307  0.008458   0.02012       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.515      0.743      0.602      0.397

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  797/7999     12.1G   0.02337  0.007959   0.01624       265       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.557      0.642      0.596      0.388

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  798/7999     12.1G   0.02397  0.008289   0.02025       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.561      0.737      0.623      0.408

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  799/7999     12.1G   0.02259  0.007726   0.01806       272       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:01<00:00,  1.14s/it]
                 all        101        130      0.598      0.739      0.632      0.397

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  800/7999     12.1G   0.02358  0.008587   0.01836       304       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.586      0.761      0.636      0.422

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  801/7999     12.1G   0.02405  0.007492   0.02036       255       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.541      0.728      0.623      0.388

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  802/7999     12.1G   0.02333  0.008581   0.01563       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.523      0.747      0.634      0.408

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  803/7999     12.1G    0.0244  0.008903   0.01921       310       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.459      0.746      0.577      0.373

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  804/7999     12.1G   0.02231   0.00793   0.01717       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.415      0.757      0.575      0.387

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  805/7999     12.1G   0.02138  0.007938   0.01496       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.433      0.721      0.587      0.389

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  806/7999     12.1G   0.02469   0.00849   0.01584       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.426        0.7      0.597      0.406

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  807/7999     12.1G   0.02353  0.008455   0.01835       302       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.14it/s]
                 all        101        130       0.45      0.721      0.603        0.4

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  808/7999     12.1G   0.02459  0.007768   0.01591       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.463      0.721      0.604      0.418

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  809/7999     12.1G   0.02332  0.007815    0.0182       277       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.428       0.71      0.594      0.423

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  810/7999     12.1G   0.02192  0.007953   0.01757       279       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.42      0.741      0.552      0.383

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  811/7999     12.1G   0.02404   0.00871   0.01909       298       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.415      0.733       0.56      0.383

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  812/7999     12.1G   0.02041   0.00726   0.01789       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.416      0.746      0.548      0.387

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  813/7999     12.1G    0.0246  0.008544   0.01846       295       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.416      0.702      0.521      0.363

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  814/7999     12.1G   0.02309  0.008352   0.01835       272       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.417      0.621      0.485      0.348

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  815/7999     12.1G   0.02334  0.009408   0.01738       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.425      0.655      0.514      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  816/7999     12.1G   0.02351  0.007972   0.01603       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.434      0.678      0.511      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  817/7999     12.1G   0.02414  0.007957   0.01979       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.438      0.654      0.506      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  818/7999     12.1G   0.02474  0.008172   0.01938       269       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.401       0.57       0.49      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  819/7999     12.1G   0.02198  0.008311   0.01444       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.607      0.412      0.503       0.34

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  820/7999     12.1G   0.02346  0.008445   0.02134       280       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.14it/s]
                 all        101        130       0.39      0.568      0.461       0.32

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  821/7999     12.1G   0.02308  0.007691    0.0194       266       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.393      0.579      0.447      0.303

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  822/7999     12.1G   0.02534  0.008706   0.01622       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.375      0.596      0.431      0.299

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  823/7999     12.1G   0.02279  0.008448   0.01636       290       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.373      0.612      0.437      0.302

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  824/7999     12.1G   0.02153  0.009223   0.01597       319       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.356      0.631      0.469      0.318

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  825/7999     12.1G   0.02232  0.008927   0.01646       295       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.332      0.636      0.473      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  826/7999     12.1G   0.02551  0.008066   0.01906       270       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.354      0.664      0.467      0.319

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  827/7999     12.1G   0.02483  0.009025   0.01421       300       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.505      0.394      0.461      0.321

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  828/7999     12.1G   0.02432  0.008235   0.02068       256       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.512      0.345      0.429      0.285

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  829/7999     12.1G   0.02207  0.007956   0.01964       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.541      0.361      0.419      0.281

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  830/7999     12.1G   0.02473  0.008942   0.01498       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.48      0.412      0.455      0.315

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  831/7999     12.1G   0.02545  0.008688   0.01708       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.512      0.427      0.507      0.351

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  832/7999     12.1G   0.02349  0.008893   0.01788       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.566      0.404      0.534      0.376

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  833/7999     12.1G   0.02314  0.007659   0.01859       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.583      0.382      0.569      0.381

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  834/7999     12.1G   0.02418  0.008004   0.01715       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.599      0.381      0.567      0.396

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  835/7999     12.1G   0.02266  0.008775   0.01771       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.598      0.397      0.564      0.373

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  836/7999     12.1G   0.02509  0.007997   0.01555       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.595      0.408      0.535      0.371

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  837/7999     12.1G   0.02271  0.008215   0.01779       261       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.726       0.38      0.502      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  838/7999     12.1G    0.0236  0.008432   0.02016       270       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.456      0.397      0.452      0.297

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  839/7999     12.1G   0.02204  0.008166   0.01651       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130       0.45      0.367      0.419      0.267

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  840/7999     12.1G    0.0252  0.008164   0.01915       272       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.515      0.365      0.465      0.309

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  841/7999     12.1G   0.02136  0.007767   0.01861       265       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.633      0.379      0.529       0.37

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  842/7999     12.1G   0.02546  0.008116   0.01828       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.566      0.406      0.518      0.368

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  843/7999     12.1G   0.02332  0.008662   0.01435       297       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.579      0.362      0.498      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  844/7999     12.1G   0.02288  0.008617   0.01788       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.584      0.437      0.515      0.361

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  845/7999     12.1G   0.02355  0.008022   0.01858       291       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.605      0.388      0.517      0.349

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  846/7999     12.1G   0.02068  0.007904   0.01561       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.623      0.355      0.515      0.348

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  847/7999     12.1G   0.02367  0.008227   0.01722       306       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.643      0.356      0.524      0.346

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  848/7999     12.1G   0.02323  0.007688   0.01921       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.643      0.392      0.515       0.34

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  849/7999     12.1G   0.02277  0.008595   0.01704       307       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.704      0.385      0.518      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  850/7999     12.1G   0.02336  0.007876   0.01664       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.707      0.362      0.535      0.349

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  851/7999     12.1G   0.02206  0.008013   0.01888       264       320: 100% 1/1 [00:01<00:00,  1.19s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130       0.69       0.35      0.534      0.363

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  852/7999     12.1G   0.02153  0.007534    0.0164       276       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.699      0.381      0.548      0.366

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  853/7999     12.1G   0.02222  0.007531   0.01631       258       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.411      0.539      0.573       0.39

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  854/7999     12.1G   0.02172    0.0076   0.01881       252       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.431      0.554       0.58      0.396

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  855/7999     12.1G    0.0221  0.007165   0.01651       253       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.718      0.404      0.591      0.412

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  856/7999     12.1G   0.02365  0.008416   0.01704       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.455      0.612      0.619      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  857/7999     12.1G   0.02458  0.008417   0.01831       302       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.46      0.634      0.622      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  858/7999     12.1G   0.02449  0.008268   0.01617       293       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.501      0.672      0.617        0.4

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  859/7999     12.1G   0.02279  0.008653    0.0166       315       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.494      0.628      0.606      0.412

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  860/7999     12.1G   0.02398  0.007689   0.02042       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.487      0.632       0.59      0.391

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  861/7999     12.1G   0.02373  0.008192   0.01796       293       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130        0.5      0.724      0.598      0.416

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  862/7999     12.1G   0.02395  0.008859   0.01678       295       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.572      0.726      0.637      0.441

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  863/7999     12.1G   0.02335  0.009186   0.01947       304       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.559      0.731      0.677       0.48

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  864/7999     12.1G    0.0241  0.008386   0.01673       294       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.573       0.71      0.707      0.486

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  865/7999     12.1G   0.02319  0.008841   0.01525       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.594      0.704        0.7      0.491

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  866/7999     12.1G   0.02493  0.009123   0.01674       310       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.606      0.673      0.681      0.449

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  867/7999     12.1G   0.02492  0.008448    0.0185       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.559       0.67       0.67      0.456

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  868/7999     12.1G   0.02337  0.008569   0.01725       299       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.525      0.681      0.644      0.436

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  869/7999     12.1G   0.02108  0.008329   0.01633       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.506      0.681      0.612      0.402

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  870/7999     12.1G   0.02655  0.007998   0.01665       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.51      0.668      0.592      0.387

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  871/7999     12.1G   0.02088  0.007896   0.01819       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.489      0.618      0.575      0.373

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  872/7999     12.1G   0.02359  0.007767   0.01751       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.418      0.539      0.538      0.337

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  873/7999     12.1G   0.02309  0.007559    0.0201       270       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.616      0.383      0.486      0.307

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  874/7999     12.1G   0.02213  0.008427   0.01808       276       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.441      0.442      0.437      0.267

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  875/7999     12.1G   0.02354  0.008244   0.01817       297       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.425      0.364      0.399      0.246

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  876/7999     12.1G   0.02042  0.007331   0.02122       262       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.377      0.457      0.452      0.272

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  877/7999     12.1G   0.02272   0.00779   0.01731       263       320: 100% 1/1 [00:01<00:00,  1.34s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.395      0.498      0.476      0.309

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  878/7999     12.1G   0.02474  0.008294   0.01772       275       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.385      0.541      0.468      0.302

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  879/7999     12.1G    0.0229  0.007864   0.01846       273       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130       0.38       0.57      0.443      0.288

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  880/7999     12.1G   0.02151    0.0074   0.01745       281       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.414      0.583      0.461       0.29

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  881/7999     12.1G   0.02459  0.008297   0.01869       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.501      0.544      0.489       0.32

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  882/7999     12.1G   0.02164  0.007937   0.01787       267       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.492      0.502      0.473      0.314

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  883/7999     12.1G   0.02158  0.007899   0.01527       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.469      0.513      0.463      0.316

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  884/7999     12.1G   0.02532  0.008768    0.0164       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.452       0.51       0.47      0.309

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  885/7999     12.1G   0.02548  0.009639   0.01613       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.448      0.542       0.49      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  886/7999     12.1G   0.02138  0.007746   0.01772       274       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.427      0.524      0.439      0.276

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  887/7999     12.1G   0.02375  0.007899   0.01733       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.399      0.492      0.421      0.264

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  888/7999     12.1G   0.02204  0.007509   0.01853       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130       0.36      0.436      0.407      0.239

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  889/7999     12.1G   0.02376  0.008032   0.01591       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.402      0.522      0.442      0.263

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  890/7999     12.1G   0.02365  0.009164   0.01693       301       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all        101        130      0.401      0.505      0.428      0.246

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  891/7999     12.1G   0.02462  0.009168   0.01773       316       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.395      0.482      0.434      0.276

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  892/7999     12.1G   0.02288  0.007333   0.01639       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.435      0.481      0.456      0.297

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  893/7999     12.1G   0.02557  0.008633   0.01687       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.444       0.49      0.448      0.312

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  894/7999     12.1G   0.02356  0.008467   0.01765       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130       0.44      0.528      0.442      0.289

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  895/7999     12.1G   0.02291  0.008083    0.0193       272       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.424      0.529       0.42       0.28

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  896/7999     12.1G   0.02286  0.008173   0.01774       291       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.435      0.541      0.424      0.284

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  897/7999     12.1G   0.02555  0.008902   0.01702       294       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.426      0.597      0.447      0.315

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  898/7999     12.1G   0.02483  0.007783   0.01954       267       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.508      0.622      0.511      0.374

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  899/7999     12.1G   0.02304  0.008396   0.01671       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.582      0.505      0.538      0.405

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  900/7999     12.1G   0.02432  0.008369   0.01677       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.603       0.51      0.586      0.417

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  901/7999     12.1G   0.02185  0.007528   0.01976       269       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.612      0.526      0.598       0.44

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  902/7999     12.1G   0.02303   0.00837   0.01845       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.578      0.508        0.6      0.418

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  903/7999     12.1G   0.02145  0.008076   0.01736       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.542       0.56      0.581      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  904/7999     12.1G   0.02623  0.008194   0.01822       269       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.552      0.504      0.564      0.403

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  905/7999     12.1G    0.0238  0.008609   0.01633       304       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.636      0.487      0.566      0.409

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  906/7999     12.1G    0.0233  0.008959   0.01674       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.596      0.506      0.568      0.404

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  907/7999     12.1G   0.02284  0.008331   0.01954       283       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.537      0.616      0.559       0.39

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  908/7999     12.1G   0.02461  0.008082   0.01826       267       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.511      0.625      0.551      0.379

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  909/7999     12.1G   0.02362  0.008425   0.01914       289       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.503      0.662       0.53      0.379

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  910/7999     12.1G     0.024  0.008086   0.01701       299       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.458      0.668      0.529      0.381

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  911/7999     12.1G   0.02378  0.008109   0.01838       289       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130       0.44      0.629      0.542      0.398

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  912/7999     12.1G   0.02278   0.00726   0.01876       261       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.782       0.35      0.523      0.391

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  913/7999     12.1G   0.02206  0.008174   0.01654       285       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.776      0.344      0.531      0.397

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  914/7999     12.1G   0.02329  0.008021   0.01617       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130       0.77       0.35      0.515      0.374

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  915/7999     12.1G   0.02048  0.007271   0.01798       253       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.746      0.347      0.484      0.347

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  916/7999     12.1G   0.02563  0.008956   0.01692       268       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.734      0.349      0.515      0.372

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  917/7999     12.1G   0.02362  0.007816   0.01962       271       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.399      0.552      0.519      0.379

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  918/7999     12.1G   0.02204  0.007974   0.01854       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.399      0.583      0.502      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  919/7999     12.1G   0.02235  0.008238   0.01537       296       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.367      0.567      0.449      0.324

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  920/7999     12.1G   0.02336  0.007997   0.02028       285       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.352      0.525      0.446      0.328

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  921/7999     12.1G   0.02316   0.00852   0.01561       310       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.371      0.506      0.409      0.305

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  922/7999     12.1G   0.02382  0.007326   0.01507       266       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.359      0.459      0.398      0.294

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  923/7999     12.1G   0.02243  0.008429   0.01815       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.337      0.472      0.395      0.286

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  924/7999     12.1G   0.02248  0.007405   0.01745       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.361      0.492      0.405      0.299

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  925/7999     12.1G   0.02563  0.008772   0.01629       294       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.349      0.512      0.413      0.295

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  926/7999     12.1G    0.0229  0.008354   0.01717       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.378      0.532       0.43       0.31

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  927/7999     12.1G   0.02252  0.008743   0.01811       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.433      0.634      0.486      0.339

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  928/7999     12.1G   0.02213  0.008469   0.01827       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.691      0.349      0.471      0.336

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  929/7999     12.1G    0.0218  0.007201   0.01943       243       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.667      0.349      0.472      0.323

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  930/7999     12.1G   0.02382  0.008781   0.01652       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.445      0.648       0.48       0.33

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  931/7999     12.1G    0.0235  0.008067   0.01948       261       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.441      0.621       0.48      0.323

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  932/7999     12.1G   0.02427  0.008114   0.01792       281       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.447       0.59      0.482      0.329

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  933/7999     12.1G   0.02277   0.00858    0.0183       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.473      0.581      0.503      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  934/7999     12.1G   0.02252   0.00824   0.01998       283       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.466      0.544      0.495      0.337

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  935/7999     12.1G   0.02409  0.007813   0.01578       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.676      0.353      0.497      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  936/7999     12.1G   0.02399  0.007743   0.01674       266       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.658      0.377       0.49      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  937/7999     12.1G   0.02362  0.009214   0.02062       296       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.676      0.348      0.493      0.336

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  938/7999     12.1G   0.02345  0.008614   0.01662       278       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.668      0.339      0.475      0.344

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  939/7999     12.1G   0.02584  0.008505   0.01655       291       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.652      0.327      0.446      0.324

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  940/7999     12.1G   0.02493  0.009309   0.01886       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130       0.66      0.338      0.429       0.31

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  941/7999     12.1G   0.02272  0.007496   0.01816       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.598      0.338      0.369      0.259

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  942/7999     12.1G   0.02366  0.009528    0.0166       309       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130        0.6      0.341      0.364      0.272

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  943/7999     12.1G   0.02413  0.008853   0.01855       313       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.607      0.356       0.37      0.269

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  944/7999     12.1G   0.02352  0.007921   0.01924       275       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.608       0.37       0.38      0.278

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  945/7999     12.1G   0.02293  0.008211    0.0173       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.609      0.352      0.389      0.281

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  946/7999     12.1G    0.0242  0.008605   0.01897       303       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all        101        130      0.627      0.397       0.41       0.31

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  947/7999     12.1G   0.02176  0.008134   0.01641       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.644      0.379      0.419      0.308

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  948/7999     12.1G   0.02332  0.008374    0.0153       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130      0.637       0.38      0.419      0.319

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  949/7999     12.1G   0.02294   0.00755   0.01682       266       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.32it/s]
                 all        101        130      0.613      0.402      0.406      0.307

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  950/7999     12.1G   0.02329  0.008077   0.01732       302       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.30it/s]
                 all        101        130      0.687      0.306      0.402      0.314

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  951/7999     12.1G   0.02329  0.007378   0.01641       241       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.33it/s]
                 all        101        130      0.667      0.355      0.428      0.323

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  952/7999     12.1G   0.02465  0.007606   0.01719       264       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.30it/s]
                 all        101        130      0.696      0.379      0.441       0.33

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  953/7999     12.1G   0.02402  0.008366   0.01929       272       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.32it/s]
                 all        101        130       0.64      0.339      0.422      0.311

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  954/7999     12.1G   0.02479  0.006772   0.01647       238       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.33it/s]
                 all        101        130      0.687       0.36      0.436      0.331

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  955/7999     12.1G    0.0242  0.007823   0.01655       265       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.35it/s]
                 all        101        130      0.665       0.36      0.429      0.322

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  956/7999     12.1G   0.02256  0.007589   0.01477       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.31it/s]
                 all        101        130      0.678       0.37       0.46      0.345

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  957/7999     12.1G   0.02365  0.007781    0.0156       285       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130      0.679       0.36      0.465      0.346

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  958/7999     12.1G   0.02291  0.008143   0.01704       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.30it/s]
                 all        101        130      0.399      0.502      0.461      0.342

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  959/7999     12.1G   0.02271  0.008567   0.01613       308       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all        101        130      0.376      0.527      0.463      0.334

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  960/7999     12.1G   0.02442  0.007765   0.01568       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.381      0.527      0.472      0.342

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  961/7999     12.1G   0.02374  0.008307   0.01792       274       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.395      0.531      0.462      0.337

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  962/7999     12.1G    0.0218  0.007761    0.0173       273       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.656      0.399      0.469      0.344

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  963/7999     12.1G   0.02285  0.007358   0.01747       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.662      0.408      0.471      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  964/7999     12.1G   0.02477  0.007887   0.01722       277       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.494      0.531      0.485      0.347

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  965/7999     12.1G   0.02541  0.009097   0.01632       333       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.503      0.555      0.501      0.348

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  966/7999     12.1G   0.02346  0.007287   0.01829       270       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.49      0.553      0.505      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  967/7999     12.1G   0.02498  0.008516   0.01583       291       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.484      0.548      0.513      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  968/7999     12.1G   0.02547  0.007399   0.01616       259       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.499      0.516      0.514      0.361

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  969/7999     12.1G   0.02305  0.008015   0.01715       266       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.66      0.396      0.517      0.365

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  970/7999     12.1G   0.02175  0.007067   0.01897       264       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.662      0.398       0.56      0.404

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  971/7999     12.1G   0.02097  0.007397   0.01559       268       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.67      0.438      0.573      0.393

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  972/7999     12.1G   0.02342  0.009109   0.01714       291       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.614      0.486       0.58      0.397

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  973/7999     12.1G   0.02194  0.008447   0.01779       274       320: 100% 1/1 [00:01<00:00,  1.19s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.556      0.494      0.565      0.369

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  974/7999     12.1G   0.02363  0.008727   0.01859       292       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.554      0.434      0.524      0.342

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  975/7999     12.1G    0.0223  0.007452   0.01905       274       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.379      0.677      0.524      0.344

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  976/7999     12.1G   0.02175  0.008115   0.01796       282       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.374      0.687      0.554      0.372

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  977/7999     12.1G   0.02348  0.008145   0.01809       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.398      0.688      0.569      0.383

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  978/7999     12.1G    0.0226  0.008581   0.01671       304       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.417      0.683      0.602      0.403

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  979/7999     12.1G   0.02163  0.008387   0.01712       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.47      0.616      0.608      0.407

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  980/7999     12.1G   0.02354   0.00809   0.01405       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.457      0.625      0.608      0.417

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  981/7999     12.1G   0.02367  0.008389   0.01665       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.439      0.663      0.604      0.417

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  982/7999     12.1G   0.02391  0.007373   0.01727       273       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.424      0.712      0.599      0.424

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  983/7999     12.1G   0.02262  0.008244   0.01702       283       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.402      0.693       0.59      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  984/7999     12.1G    0.0252  0.008641   0.01588       299       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.417      0.704      0.609      0.444

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  985/7999     12.1G   0.02304   0.00868    0.0158       322       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.42      0.711      0.598      0.414

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  986/7999     12.1G    0.0254  0.008805   0.01675       292       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.419      0.688      0.599      0.422

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  987/7999     12.1G   0.02274  0.007797   0.01653       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.679      0.432      0.595      0.423

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  988/7999     12.1G   0.02258   0.00856   0.01715       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.663      0.426      0.575      0.413

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  989/7999     12.1G   0.02472  0.007302   0.01923       236       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.631      0.379       0.54      0.389

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  990/7999     12.1G   0.02446  0.008895   0.01955       306       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.648      0.416      0.541      0.396

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  991/7999     12.1G   0.02268   0.00836   0.01805       278       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.638      0.395       0.54      0.393

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  992/7999     12.1G   0.02358  0.007782   0.01731       267       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.634      0.401       0.52      0.378

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  993/7999     12.1G   0.02227  0.007896   0.01431       295       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.649      0.408      0.542      0.383

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  994/7999     12.1G   0.02398  0.008169   0.01641       282       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.649      0.439      0.551      0.406

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  995/7999     12.1G    0.0237  0.008919    0.0165       291       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.633      0.425      0.578      0.412

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  996/7999     12.1G   0.02293    0.0082   0.01672       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.604       0.46      0.595      0.426

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  997/7999     12.1G   0.02253  0.007122   0.01777       269       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.699      0.406      0.613      0.423

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  998/7999     12.1G   0.02488  0.007668   0.01623       262       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.687      0.422      0.624      0.435

     Epoch   gpu_mem       box       obj       cls    labels  img_size
  999/7999     12.1G   0.02297  0.007685   0.01664       266       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.768       0.38       0.63      0.437

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1000/7999     12.1G   0.02215  0.007971   0.01633       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.764      0.401      0.635      0.439

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1001/7999     12.1G   0.02346  0.007959   0.01474       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.808      0.401      0.633      0.432

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1002/7999     12.1G   0.02336  0.007724   0.01528       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.813      0.404      0.627      0.435

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1003/7999     12.1G   0.02345  0.008445   0.01578       303       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.11it/s]
                 all        101        130      0.803      0.398      0.612      0.416

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1004/7999     12.1G   0.02256  0.008071   0.01652       275       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.893      0.376      0.598      0.407

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1005/7999     12.1G   0.02379  0.007345   0.01832       267       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.723      0.405      0.582      0.395

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1006/7999     12.1G   0.02422  0.008189    0.0201       291       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.648      0.385      0.512      0.355

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1007/7999     12.1G   0.02218  0.008298    0.0162       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130       0.63      0.409      0.482      0.339

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1008/7999     12.1G   0.02406   0.00803   0.01657       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.628      0.415      0.527      0.376

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1009/7999     12.1G   0.02193  0.007273   0.01849       270       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.593      0.438      0.568      0.399

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1010/7999     12.1G   0.02245  0.007665   0.01847       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.613       0.46       0.57      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1011/7999     12.1G   0.02326  0.007771   0.01883       272       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.575      0.438      0.535      0.391

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1012/7999     12.1G   0.02136  0.007684   0.01456       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.524      0.445      0.505      0.365

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1013/7999     12.1G    0.0218  0.008164   0.01853       286       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.384       0.52      0.547      0.369

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1014/7999     12.1G   0.02226  0.008774   0.01708       304       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.41       0.58      0.567      0.371

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1015/7999     12.1G   0.02376  0.007883   0.01676       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.474      0.471       0.55      0.346

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1016/7999     12.1G   0.02157   0.00822   0.01645       304       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.406      0.535      0.558      0.361

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1017/7999     12.1G   0.02185  0.007341   0.01844       251       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.412      0.568      0.559      0.357

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1018/7999     12.1G   0.02244  0.007751   0.01803       286       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.415      0.558      0.572      0.386

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1019/7999     12.1G   0.02218  0.007312   0.01864       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.421      0.542       0.59      0.403

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1020/7999     12.1G   0.02181  0.008269   0.01736       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.667      0.408      0.571       0.41

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1021/7999     12.1G   0.02424  0.008329   0.01982       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.661      0.396      0.567        0.4

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1022/7999     12.1G   0.02092  0.007275   0.01372       264       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.596      0.427      0.563      0.409

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1023/7999     12.1G   0.02143  0.007472   0.01881       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.688      0.371      0.553      0.382

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1024/7999     12.1G   0.02432  0.007831   0.02089       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.575      0.437       0.56      0.394

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1025/7999     12.1G   0.02162   0.00793   0.01782       283       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.568      0.415      0.556      0.372

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1026/7999     12.1G   0.02309  0.008055   0.01438       283       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.708      0.383      0.561      0.374

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1027/7999     12.1G   0.02414  0.008178   0.01657       283       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.63      0.382      0.553      0.356

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1028/7999     12.1G   0.02302  0.006579   0.01759       254       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.578      0.438      0.532      0.356

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1029/7999     12.1G    0.0216  0.008187    0.0168       283       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.567      0.433       0.51      0.343

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1030/7999     12.1G   0.02245  0.007829   0.01487       265       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.713       0.33      0.493      0.331

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1031/7999     12.1G   0.02304  0.007905   0.01833       278       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.691      0.372      0.485      0.314

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1032/7999     12.1G   0.02114  0.007781   0.01981       278       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.671       0.36      0.481       0.31

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1033/7999     12.1G   0.02215  0.007863   0.01779       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.665      0.342      0.497      0.317

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1034/7999     12.1G   0.02143  0.006832   0.01647       265       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130        0.7       0.35        0.5      0.324

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1035/7999     12.1G   0.02038  0.008162   0.01597       286       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.723      0.329      0.509      0.325

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1036/7999     12.1G   0.02342  0.007972   0.01616       295       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.703      0.335      0.487       0.31

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1037/7999     12.1G    0.0211  0.007234   0.01954       270       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130       0.43      0.483      0.478      0.307

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1038/7999     12.1G    0.0223  0.007574   0.01583       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.439      0.483       0.48      0.305

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1039/7999     12.1G   0.02424  0.007612   0.01688       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.448      0.481      0.486      0.324

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1040/7999     12.1G   0.02182  0.007727   0.01801       297       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.455      0.488      0.478       0.32

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1041/7999     12.1G   0.02289  0.008009   0.01788       300       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.427      0.513       0.48      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1042/7999     12.1G   0.02439  0.008551    0.0154       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.414      0.491      0.482      0.321

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1043/7999     12.1G   0.02274  0.007675   0.01942       296       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.411       0.48      0.492      0.326

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1044/7999     12.1G   0.02137  0.007721   0.01508       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.423      0.537      0.493      0.323

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1045/7999     12.1G    0.0225  0.008892   0.01811       318       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.44      0.613      0.502      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1046/7999     12.1G   0.02053  0.006697   0.01824       255       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.478      0.558      0.507      0.337

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1047/7999     12.1G   0.02314  0.007096   0.01519       246       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.433      0.662      0.506      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1048/7999     12.1G   0.02453  0.007853   0.01739       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.429      0.655      0.496      0.324

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1049/7999     12.1G   0.02289  0.007394   0.01539       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.436      0.629      0.474      0.318

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1050/7999     12.1G   0.02386  0.007903    0.0185       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.445      0.606      0.477       0.33

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1051/7999     12.1G   0.02283  0.008182   0.01523       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.438       0.59      0.486      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1052/7999     12.1G   0.02273  0.007946   0.01662       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.439      0.591      0.494      0.344

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1053/7999     12.1G   0.02263  0.007687   0.01929       266       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.439      0.615      0.483      0.319

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1054/7999     12.1G   0.02067  0.007516    0.0231       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.482      0.573      0.473      0.318

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1055/7999     12.1G   0.02406  0.007551   0.01851       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.457      0.565      0.482      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1056/7999     12.1G   0.02255  0.008014   0.01958       265       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.439      0.579      0.475      0.335

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1057/7999     12.1G   0.02166   0.00761   0.01488       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.437      0.617      0.484      0.341

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1058/7999     12.1G   0.02291  0.008417   0.01745       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.44      0.612      0.507      0.358

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1059/7999     12.1G   0.02329  0.007725   0.01871       271       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.436       0.59      0.503      0.361

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1060/7999     12.1G   0.02254  0.008142   0.01691       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.452      0.592        0.5      0.355

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1061/7999     12.1G   0.02303  0.007801   0.01694       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.431      0.604      0.493      0.353

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1062/7999     12.1G   0.02251  0.008309   0.01762       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.53      0.419      0.464      0.336

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1063/7999     12.1G   0.02111  0.008152   0.01492       298       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.14it/s]
                 all        101        130      0.436      0.516      0.433      0.306

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1064/7999     12.1G   0.02385    0.0079   0.01822       304       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.634      0.351      0.398      0.283

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1065/7999     12.1G   0.02292  0.008158    0.0172       289       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130       0.59      0.367       0.39      0.266

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1066/7999     12.1G   0.02469  0.009043   0.01665       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.686      0.283      0.371      0.234

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1067/7999     12.1G   0.02494   0.00806   0.02083       276       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.31it/s]
                 all        101        130      0.651      0.286      0.371      0.228

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1068/7999     12.1G   0.02126  0.008839   0.01417       300       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.653      0.354      0.414      0.268

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1069/7999     12.1G   0.02277  0.007482   0.01904       259       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.574      0.396      0.483      0.342

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1070/7999     12.1G   0.02305  0.008283   0.01921       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.813      0.316      0.523      0.389

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1071/7999     12.1G   0.02415  0.008128   0.01634       290       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130       0.65      0.404      0.512      0.366

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1072/7999     12.1G   0.02622  0.008279   0.01838       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.656      0.399      0.513      0.377

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1073/7999     12.1G   0.02011  0.007327   0.01749       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.651      0.397      0.527      0.392

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1074/7999     12.1G   0.02123  0.008314   0.01539       297       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.711      0.339      0.521       0.38

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1075/7999     12.1G   0.02239  0.008074   0.01751       271       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.612      0.352      0.507      0.353

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1076/7999     12.1G   0.02379  0.008331     0.016       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.458      0.481      0.478      0.337

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1077/7999     12.1G   0.02152  0.008073   0.01674       290       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.453      0.472      0.479      0.317

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1078/7999     12.1G    0.0247  0.008579   0.01996       274       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.458      0.419      0.463      0.313

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1079/7999     12.1G   0.02256  0.008225   0.01654       291       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.443      0.447      0.462        0.3

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1080/7999     12.1G   0.02343  0.007944   0.01626       297       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.616      0.328      0.445      0.306

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1081/7999     12.1G   0.02281  0.007842    0.0168       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.615      0.321      0.429      0.281

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1082/7999     12.1G   0.02433  0.008687   0.01772       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.626      0.299      0.439        0.3

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1083/7999     12.1G   0.02484  0.008368   0.01547       279       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.628      0.268      0.417      0.276

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1084/7999     12.1G   0.02385  0.008188   0.01807       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.485      0.515      0.419      0.292

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1085/7999     12.1G   0.02153  0.007332   0.01695       268       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.485      0.484      0.413      0.272

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1086/7999     12.1G   0.02332   0.00883    0.0156       295       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.504      0.459      0.407      0.276

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1087/7999     12.1G   0.02208  0.008032   0.01991       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.477      0.449      0.411      0.268

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1088/7999     12.1G    0.0218  0.007372   0.01671       259       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.496      0.445      0.398      0.263

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1089/7999     12.1G   0.02363  0.008398   0.01912       296       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.474      0.394       0.38      0.239

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1090/7999     12.1G   0.02176  0.008502   0.01521       306       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.495      0.398      0.391      0.249

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1091/7999     12.1G   0.02349  0.007629   0.01809       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.474      0.404      0.397      0.249

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1092/7999     12.1G   0.02193  0.008466   0.01481       298       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.476      0.445      0.451      0.279

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1093/7999     12.1G   0.02381  0.008354   0.01838       289       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.13it/s]
                 all        101        130      0.463      0.472      0.466      0.296

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1094/7999     12.1G   0.02137  0.007036   0.01687       267       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.416      0.455       0.49      0.321

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1095/7999     12.1G   0.02319  0.008311    0.0145       291       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.439       0.46      0.515      0.343

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1096/7999     12.1G   0.02304  0.008624   0.01391       298       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.474       0.61      0.566      0.391

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1097/7999     12.1G   0.02143  0.007498   0.01533       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.509      0.693      0.603      0.417

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1098/7999     12.1G   0.02405  0.007785   0.01462       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.522      0.752      0.629       0.43

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1099/7999     12.1G   0.02148  0.007323   0.01744       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.531      0.787      0.649      0.448

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1100/7999     12.1G   0.02137  0.007467   0.01728       264       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.526      0.745      0.641      0.454

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1101/7999     12.1G   0.02374  0.008171   0.01688       267       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.501      0.746      0.628      0.449

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1102/7999     12.1G   0.02363  0.007537   0.01608       281       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.471      0.684      0.618      0.451

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1103/7999     12.1G   0.02199  0.008346     0.016       313       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.456      0.694      0.617      0.454

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1104/7999     12.1G   0.02194  0.007397    0.0155       279       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.463      0.748      0.613      0.447

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1105/7999     12.1G    0.0252  0.007925   0.02183       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130       0.47       0.75      0.598      0.428

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1106/7999     12.1G   0.01837  0.007227    0.0197       261       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.457      0.713      0.599      0.409

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1107/7999     12.1G    0.0237  0.007231   0.01786       267       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.456      0.677      0.592      0.402

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1108/7999     12.1G   0.02129  0.007592   0.02023       270       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.449       0.66      0.581      0.405

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1109/7999     12.1G   0.02281  0.007829    0.0211       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.452      0.655      0.557      0.385

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1110/7999     12.1G   0.02077  0.007409   0.01866       275       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.441      0.616       0.55      0.382

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1111/7999     12.1G   0.02351  0.007856   0.01692       283       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.416      0.518      0.559      0.381

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1112/7999     12.1G   0.02144  0.008426   0.01548       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.367      0.497      0.535      0.348

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1113/7999     12.1G   0.02243  0.007483   0.01481       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.375      0.497      0.533      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1114/7999     12.1G   0.02291  0.008246   0.01489       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.332      0.504      0.479      0.321

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1115/7999     12.1G   0.02131  0.007688   0.01994       266       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.372      0.521       0.49      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1116/7999     12.1G    0.0226  0.008522   0.02035       297       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.585      0.394      0.538      0.368

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1117/7999     12.1G   0.02008  0.007767   0.01851       272       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.729      0.461      0.612      0.431

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1118/7999     12.1G    0.0214  0.007998   0.01814       281       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.695      0.423        0.6      0.411

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1119/7999     12.1G   0.02161  0.008484   0.01691       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.618       0.38      0.576      0.391

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1120/7999     12.1G   0.02251  0.007988   0.01525       296       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.537        0.5      0.546       0.38

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1121/7999     12.1G   0.02052  0.007211   0.01689       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.536      0.506      0.521      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1122/7999     12.1G   0.02073  0.007089   0.01678       267       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.533      0.468      0.491      0.339

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1123/7999     12.1G   0.02146  0.008169   0.01643       280       320: 100% 1/1 [00:01<00:00,  1.19s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.561      0.455      0.485      0.338

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1124/7999     12.1G    0.0225   0.00761   0.01827       285       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.514      0.408      0.502       0.35

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1125/7999     12.1G   0.02295  0.007966   0.01658       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.578      0.386      0.495      0.347

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1126/7999     12.1G    0.0231  0.008896   0.01557       312       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130       0.59      0.396      0.488      0.344

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1127/7999     12.1G   0.02264   0.00828   0.01975       271       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.414      0.555      0.474      0.336

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1128/7999     12.1G   0.02402  0.008493   0.01892       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.377      0.629      0.467      0.322

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1129/7999     12.1G   0.02201  0.008134   0.01837       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.298      0.752      0.444      0.302

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1130/7999     12.1G   0.02185  0.007753   0.01581       275       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130       0.38      0.665      0.443      0.288

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1131/7999     12.1G   0.02354  0.008917   0.01673       303       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.458      0.629      0.454      0.295

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1132/7999     12.1G   0.02136  0.008177   0.01712       265       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.403      0.605      0.466      0.294

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1133/7999     12.1G   0.02157  0.008666   0.01788       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.414        0.6      0.484      0.315

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1134/7999     12.1G   0.02139  0.007833   0.01609       276       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.423      0.603      0.513      0.328

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1135/7999     12.1G   0.02326  0.007653    0.0177       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.399      0.584      0.511       0.33

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1136/7999     12.1G   0.02293  0.008494   0.01328       298       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.468       0.63      0.525      0.324

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1137/7999     12.1G   0.02264  0.007769   0.01671       268       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.364      0.774      0.533       0.35

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1138/7999     12.1G   0.02619  0.008864   0.01582       300       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.371      0.719      0.542      0.353

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1139/7999     12.1G   0.02385  0.008421   0.01629       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.343      0.891      0.542      0.362

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1140/7999     12.1G     0.023  0.008033   0.01819       280       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.253       0.96       0.54       0.35

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1141/7999     12.1G    0.0225  0.007094   0.01667       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.288      0.956      0.554      0.366

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1142/7999     12.1G   0.02482  0.008702   0.01719       303       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.657      0.402      0.544      0.369

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1143/7999     12.1G   0.02105  0.007462   0.01722       265       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.353      0.761      0.555      0.379

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1144/7999     12.1G   0.02416  0.009192   0.01803       309       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.405      0.656      0.567      0.383

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1145/7999     12.1G   0.02276  0.007447   0.02113       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.404      0.657      0.579      0.402

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1146/7999     12.1G   0.02064  0.007753   0.01607       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.399      0.677      0.568      0.385

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1147/7999     12.1G   0.02358  0.008568    0.0165       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.409       0.67      0.592      0.405

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1148/7999     12.1G   0.02167  0.008049    0.0164       308       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.401      0.669      0.585      0.404

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1149/7999     12.1G   0.02446  0.008849   0.01873       311       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.348      0.628      0.566      0.377

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1150/7999     12.1G   0.02338  0.007966   0.01757       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.376      0.638      0.559      0.374

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1151/7999     12.1G   0.02237  0.007653   0.01425       293       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.391      0.629      0.533      0.348

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1152/7999     12.1G   0.02448  0.007674    0.0158       280       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.395      0.615      0.537      0.351

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1153/7999     12.1G   0.02217  0.007017   0.01824       272       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.405      0.595      0.517      0.344

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1154/7999     12.1G   0.02228  0.008227   0.01594       302       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.411      0.537      0.521      0.356

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1155/7999     12.1G   0.02146   0.00805   0.01541       291       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.416      0.518       0.51      0.349

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1156/7999     12.1G   0.02154  0.008058   0.01773       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.425      0.525      0.495      0.341

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1157/7999     12.1G   0.02221  0.008115   0.01554       300       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.444      0.578      0.481      0.338

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1158/7999     12.1G   0.02506  0.008161   0.01518       283       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.427       0.55      0.478      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1159/7999     12.1G   0.02361  0.008189   0.01594       295       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.441       0.51      0.475      0.337

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1160/7999     12.1G   0.02266  0.007311   0.01778       265       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.445      0.514      0.474      0.335

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1161/7999     12.1G   0.02252  0.007124   0.01721       270       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.451      0.514      0.475      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1162/7999     12.1G   0.02086  0.007499   0.01973       269       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.442      0.482      0.461      0.322

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1163/7999     12.1G   0.02235  0.007491    0.0167       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.454      0.515      0.455      0.314

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1164/7999     12.1G   0.02205  0.007483   0.01569       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.451      0.485      0.458      0.319

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1165/7999     12.1G   0.02157  0.007493   0.01623       281       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.426      0.452      0.452      0.313

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1166/7999     12.1G    0.0232  0.006819   0.01791       249       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.429      0.463      0.464       0.33

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1167/7999     12.1G   0.02219  0.007343   0.01924       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.776      0.287      0.477      0.337

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1168/7999     12.1G   0.02293  0.008318   0.01636       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.763      0.293      0.461      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1169/7999     12.1G   0.02203  0.008112   0.01757       283       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.739      0.306      0.434      0.318

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1170/7999     12.1G   0.02058  0.008079   0.01508       295       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.708      0.311      0.463      0.334

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1171/7999     12.1G   0.02175  0.007252   0.01798       253       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.692      0.331        0.5      0.356

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1172/7999     12.1G   0.02135   0.00698    0.0158       274       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130        0.6       0.41      0.523      0.376

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1173/7999     12.1G   0.02133  0.007769   0.01947       295       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.615      0.421      0.532      0.379

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1174/7999     12.1G   0.02263  0.008556   0.01548       300       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.617      0.441      0.552      0.389

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1175/7999     12.1G    0.0224  0.006752   0.01923       254       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.595      0.456      0.561       0.38

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1176/7999     12.1G    0.0202  0.007132   0.01646       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130       0.43      0.591      0.545      0.371

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1177/7999     12.1G   0.02287  0.009364   0.01596       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.423      0.587      0.542      0.365

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1178/7999     12.1G   0.02109  0.008083   0.01783       269       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.441      0.615      0.551      0.381

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1179/7999     12.1G   0.02095  0.007946   0.01578       280       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.427      0.597      0.564      0.398

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1180/7999     12.1G   0.02396  0.008285   0.01734       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.439      0.633      0.564      0.388

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1181/7999     12.1G   0.02301  0.007129   0.01732       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.438      0.714      0.564      0.401

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1182/7999     12.1G   0.02339  0.009138    0.0166       315       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.12it/s]
                 all        101        130      0.455      0.741      0.559      0.392

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1183/7999     12.1G   0.02253  0.007707   0.02031       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.436      0.696      0.545      0.397

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1184/7999     12.1G   0.02423  0.008219   0.01417       303       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.431      0.709      0.509      0.364

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1185/7999     12.1G   0.02319  0.008634   0.01555       292       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.417      0.666      0.507      0.365

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1186/7999     12.1G   0.02135  0.008264   0.01848       300       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.373      0.597      0.508      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1187/7999     12.1G    0.0214  0.008088   0.01945       297       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.453      0.609      0.526      0.369

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1188/7999     12.1G   0.02341  0.007662   0.01276       296       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.502      0.603      0.532       0.37

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1189/7999     12.1G   0.02228  0.007081   0.02023       261       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.413      0.608      0.516      0.367

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1190/7999     12.1G   0.02212  0.008617   0.01853       299       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130       0.35      0.624      0.474      0.331

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1191/7999     12.1G   0.02336  0.007959   0.02087       281       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.288      0.578      0.332      0.222

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1192/7999     12.1G   0.02107  0.007909    0.0207       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.299      0.516      0.378      0.254

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1193/7999     12.1G   0.02119  0.007621   0.01855       270       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.295      0.605      0.402       0.27

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1194/7999     12.1G    0.0225  0.008336   0.01664       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.324      0.626      0.459      0.312

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1195/7999     12.1G   0.02315  0.007057   0.01941       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.362      0.681      0.463      0.303

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1196/7999     12.1G   0.01944  0.007619   0.01787       294       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.412      0.747      0.497      0.311

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1197/7999     12.1G   0.02245   0.00762   0.02095       266       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.439      0.771      0.498        0.3

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1198/7999     12.1G   0.02303  0.009922   0.01624       325       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.456      0.759      0.545      0.315

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1199/7999     12.1G   0.02274  0.007266   0.01863       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.429      0.691      0.512      0.309

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1200/7999     12.1G   0.02165  0.007159    0.0198       261       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.405      0.586      0.434      0.271

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1201/7999     12.1G    0.0239  0.008699    0.0183       289       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.39      0.552      0.392      0.244

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1202/7999     12.1G   0.02211  0.007137   0.02067       261       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.533      0.402      0.434      0.269

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1203/7999     12.1G    0.0221  0.007742   0.01683       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.448      0.552      0.484      0.293

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1204/7999     12.1G   0.02328   0.00771   0.01835       280       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.463      0.563       0.49      0.316

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1205/7999     12.1G   0.02278   0.00854   0.01722       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.446      0.547      0.482      0.315

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1206/7999     12.1G    0.0205  0.007526   0.02202       273       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.456       0.62      0.484      0.328

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1207/7999     12.1G   0.02328  0.007581   0.01934       280       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.457      0.652      0.499      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1208/7999     12.1G   0.02111  0.007266    0.0163       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.477        0.7      0.529      0.355

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1209/7999     12.1G   0.02225  0.007395   0.01666       280       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.483      0.721      0.529      0.341

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1210/7999     12.1G   0.02335  0.007588   0.01605       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.492      0.745      0.543      0.352

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1211/7999     12.1G   0.02331  0.009029   0.01539       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.474      0.758       0.54      0.351

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1212/7999     12.1G   0.02181  0.007654   0.01679       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.11it/s]
                 all        101        130      0.487      0.771      0.548      0.364

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1213/7999     12.1G   0.02114  0.007982   0.01753       290       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.479      0.792      0.541       0.36

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1214/7999     12.1G    0.0221  0.008945   0.01764       312       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.478      0.794      0.569      0.374

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1215/7999     12.1G   0.02252  0.007441   0.01646       274       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.449      0.748      0.555      0.359

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1216/7999     12.1G   0.02389  0.007107     0.016       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.445      0.711      0.544      0.359

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1217/7999     12.1G   0.02294  0.008249   0.01747       263       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.445      0.637      0.547      0.376

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1218/7999     12.1G   0.02088  0.007423   0.01704       267       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.429      0.511      0.533      0.372

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1219/7999     12.1G   0.02336  0.008107   0.01782       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.448      0.558      0.562      0.394

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1220/7999     12.1G   0.02283  0.007106   0.01676       259       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.41      0.555      0.569      0.402

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1221/7999     12.1G   0.02266  0.007361   0.01553       268       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.414      0.508      0.561      0.389

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1222/7999     12.1G    0.0242  0.008373   0.01426       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.617      0.337      0.522      0.357

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1223/7999     12.1G   0.02156  0.007511     0.016       264       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.497      0.371       0.46      0.312

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1224/7999     12.1G   0.02156  0.007304   0.01733       277       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.536      0.298      0.441      0.302

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1225/7999     12.1G   0.02437  0.007739   0.01638       291       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.505      0.334      0.454      0.314

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1226/7999     12.1G   0.02217  0.007653   0.01609       298       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130       0.55      0.326      0.454      0.313

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1227/7999     12.1G   0.02313  0.007836   0.01875       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.28it/s]
                 all        101        130      0.563      0.338      0.453      0.307

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1228/7999     12.1G   0.02198  0.007107   0.01852       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.572      0.369       0.47      0.329

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1229/7999     12.1G   0.01844   0.00811    0.0179       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.579      0.376      0.493      0.348

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1230/7999     12.1G   0.02032  0.007387   0.01738       283       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.611      0.422       0.54       0.38

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1231/7999     12.1G   0.02244  0.007936   0.02019       272       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.642      0.424      0.567      0.396

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1232/7999     12.1G   0.02063  0.007993   0.01639       303       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.649      0.454      0.598      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1233/7999     12.1G   0.02164    0.0077   0.01865       281       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.612       0.44      0.588      0.412

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1234/7999     12.1G   0.02507  0.008164    0.0173       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.715      0.377      0.548      0.396

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1235/7999     12.1G   0.02456  0.007808   0.01771       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.604      0.378      0.513      0.367

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1236/7999     12.1G   0.02227  0.008666     0.017       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130      0.581      0.364      0.508      0.367

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1237/7999     12.1G   0.02363  0.008114   0.01649       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.553      0.382      0.475       0.34

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1238/7999     12.1G   0.02348  0.008275   0.01703       276       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.544      0.392      0.452      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1239/7999     12.1G   0.02412   0.00857    0.0193       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.612      0.282      0.425      0.302

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1240/7999     12.1G   0.02352  0.008074   0.01561       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130      0.581      0.313      0.418      0.304

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1241/7999     12.1G   0.02365  0.007234   0.01685       267       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.613      0.297      0.392      0.274

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1242/7999     12.1G     0.023  0.008007   0.01658       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130      0.636      0.311      0.416      0.302

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1243/7999     12.1G    0.0222  0.008323   0.01618       289       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.642      0.294        0.4      0.281

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1244/7999     12.1G    0.0209  0.006955   0.01922       251       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.30it/s]
                 all        101        130      0.674      0.222      0.313      0.224

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1245/7999     12.1G   0.02221  0.008174   0.01574       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.29it/s]
                 all        101        130      0.532      0.208      0.254      0.179

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1246/7999     12.1G   0.02208  0.008005   0.01763       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130      0.563       0.18      0.227       0.16

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1247/7999     12.1G   0.02376  0.008356   0.01772       312       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.27it/s]
                 all        101        130       0.53      0.227       0.25      0.176

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1248/7999     12.1G   0.02089  0.009356   0.01285       331       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.643      0.202      0.296      0.214

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1249/7999     12.1G   0.02152  0.006794   0.01746       250       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.657      0.223      0.324      0.233

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1250/7999     12.1G   0.02458  0.008365    0.0149       285       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.41      0.424      0.362       0.27

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1251/7999     12.1G   0.02229  0.008005   0.01456       296       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.426      0.475      0.399       0.29

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1252/7999     12.1G   0.02247  0.008285   0.01762       276       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.452      0.527       0.47      0.348

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1253/7999     12.1G   0.02089  0.007387   0.01582       265       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.646      0.347      0.483      0.346

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1254/7999     12.1G   0.02097  0.008138   0.01396       306       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.591      0.408      0.512      0.365

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1255/7999     12.1G   0.02235  0.008737   0.01639       318       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.626      0.523      0.571      0.396

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1256/7999     12.1G    0.0226  0.008047   0.01636       289       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.644      0.543      0.629      0.436

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1257/7999     12.1G   0.02215  0.007859   0.01823       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.73      0.495      0.647      0.459

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1258/7999     12.1G   0.02004  0.008736   0.01665       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.639      0.513      0.647      0.473

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1259/7999     12.1G   0.02305  0.007684   0.01736       288       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.565      0.438      0.612      0.442

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1260/7999     12.1G   0.02154  0.008243   0.01605       307       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.547      0.518      0.562      0.398

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1261/7999     12.1G   0.02269  0.008362   0.01664       319       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.664      0.365       0.52      0.351

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1262/7999     12.1G   0.02281  0.008532   0.01501       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.528      0.567      0.498      0.319

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1263/7999     12.1G   0.02247   0.00797   0.01561       283       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.651      0.445      0.575      0.395

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1264/7999     12.1G   0.02491  0.008725   0.01788       304       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.504      0.641      0.573      0.406

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1265/7999     12.1G   0.02072  0.007135   0.01671       279       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.708       0.36      0.553      0.384

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1266/7999     12.1G   0.02325  0.007532   0.01751       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.704       0.31      0.531       0.37

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1267/7999     12.1G   0.02346  0.008104   0.01674       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.647      0.305      0.491      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1268/7999     12.1G   0.02106  0.007947   0.01836       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.36      0.605      0.455      0.323

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1269/7999     12.1G   0.02118   0.00756   0.01444       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.367      0.551      0.452      0.303

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1270/7999     12.1G   0.02427  0.008021   0.01734       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.363       0.54      0.435      0.304

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1271/7999     12.1G   0.02184  0.007216   0.01921       276       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.346      0.568       0.43      0.287

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1272/7999     12.1G   0.02107  0.007762   0.01593       272       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.133      0.905      0.363      0.183

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1273/7999     12.1G   0.02142  0.009361   0.01714       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.834      0.108      0.256      0.127

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1274/7999     12.1G   0.02377  0.008948   0.01587       308       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.494       0.11      0.224      0.114

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1275/7999     12.1G   0.02058  0.007602   0.01535       272       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.512      0.108      0.223      0.114

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1276/7999     12.1G   0.02259  0.008253   0.01773       279       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130       0.51      0.118      0.235      0.126

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1277/7999     12.1G    0.0236  0.008527   0.01612       293       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.461       0.16      0.264      0.155

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1278/7999     12.1G   0.02102  0.007529   0.01709       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.195      0.848      0.349      0.222

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1279/7999     12.1G   0.02118  0.007365   0.01606       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.467      0.441      0.477      0.334

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1280/7999     12.1G   0.02275   0.00836   0.01802       298       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.425      0.619      0.529      0.366

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1281/7999     12.1G   0.02382  0.007989    0.0188       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.414      0.661      0.552      0.379

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1282/7999     12.1G   0.02291   0.00709    0.0187       270       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.559      0.381      0.568      0.399

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1283/7999     12.1G   0.02067  0.008909   0.01969       281       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.434      0.535      0.545      0.376

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1284/7999     12.1G   0.02159  0.008035   0.01685       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.449      0.537      0.504      0.336

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1285/7999     12.1G   0.02004  0.007704   0.01821       285       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.444       0.61      0.496      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1286/7999     12.1G   0.02184  0.008197   0.01718       309       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.433      0.574      0.494      0.333

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1287/7999     12.1G   0.02203  0.007745   0.01996       273       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.416      0.564      0.474      0.317

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1288/7999     12.1G   0.02137  0.007761   0.01725       300       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.367      0.553      0.448      0.303

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1289/7999     12.1G   0.02118  0.007296   0.01452       250       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.368      0.575      0.454       0.31

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1290/7999     12.1G   0.02107  0.007825   0.01692       285       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.663      0.291      0.468      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1291/7999     12.1G    0.0226  0.008604   0.01669       301       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.608      0.333      0.485      0.339

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1292/7999     12.1G   0.02242  0.007083   0.02035       246       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.669      0.328      0.493      0.343

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1293/7999     12.1G   0.02085  0.008595   0.01732       310       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.746      0.315      0.492      0.329

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1294/7999     12.1G   0.02395  0.007967   0.01415       281       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.767      0.324      0.499      0.358

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1295/7999     12.1G   0.02082  0.007717   0.01847       269       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.694      0.323      0.482      0.339

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1296/7999     12.1G   0.02194  0.008211   0.01719       282       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.626      0.346      0.428      0.311

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1297/7999     12.1G   0.02468  0.008751   0.01776       296       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.553      0.335      0.413      0.291

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1298/7999     12.1G   0.02401   0.01011   0.01549       321       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.644      0.279      0.401      0.293

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1299/7999     12.1G   0.02076  0.007951   0.01769       294       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.615      0.316       0.41      0.294

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1300/7999     12.1G   0.02388  0.007695   0.01601       278       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.667      0.309      0.422      0.307

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1301/7999     12.1G   0.02368  0.007884   0.01597       268       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.682      0.306      0.444      0.318

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1302/7999     12.1G   0.02081  0.007582   0.01686       262       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.706      0.298      0.447      0.325

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1303/7999     12.1G   0.02349  0.007739    0.0176       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.743      0.298      0.465       0.33

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1304/7999     12.1G   0.02395  0.007562   0.01528       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.751       0.29      0.466      0.332

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1305/7999     12.1G   0.01885  0.007062   0.01955       257       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.24it/s]
                 all        101        130      0.704      0.298       0.46      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1306/7999     12.1G   0.01996  0.007275   0.01638       286       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.659      0.319      0.472      0.341

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1307/7999     12.1G   0.02237  0.007617    0.0155       297       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.271      0.737      0.456      0.325

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1308/7999     12.1G   0.02243   0.00697   0.01488       272       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.206      0.831      0.419      0.312

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1309/7999     12.1G    0.0225  0.007187   0.02002       249       320: 100% 1/1 [00:01<00:00,  1.36s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.321      0.772      0.421      0.306

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1310/7999     12.1G   0.02162  0.007317   0.01585       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.315      0.795       0.42      0.309

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1311/7999     12.1G   0.02316  0.007606   0.01884       268       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.285      0.806      0.404      0.286

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1312/7999     12.1G   0.02394  0.008132   0.01885       270       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.289      0.814      0.388      0.281

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1313/7999     12.1G   0.02047  0.008416   0.01836       291       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.392      0.615      0.422        0.3

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1314/7999     12.1G    0.0212  0.007322    0.0175       286       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.429      0.656      0.472      0.331

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1315/7999     12.1G   0.02214  0.007746   0.01645       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.421      0.638      0.463       0.32

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1316/7999     12.1G    0.0207   0.00758   0.01632       295       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.433      0.625      0.441       0.29

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1317/7999     12.1G   0.02211   0.00832   0.01301       309       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.537      0.423      0.422      0.283

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1318/7999     12.1G   0.01981  0.007355   0.01973       263       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.501      0.392      0.382      0.254

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1319/7999     12.1G   0.02145  0.008001   0.01761       272       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.45       0.37       0.33      0.213

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1320/7999     12.1G   0.02242  0.007771   0.01845       295       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.546      0.321      0.379       0.25

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1321/7999     12.1G   0.02226  0.007998   0.01757       281       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.589      0.444      0.474      0.325

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1322/7999     12.1G   0.02231  0.008289   0.01593       304       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.14it/s]
                 all        101        130      0.644      0.429      0.528      0.378

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1323/7999     12.1G   0.02196  0.008055   0.01829       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.636      0.495      0.541      0.387

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1324/7999     12.1G   0.02142  0.007541   0.01779       288       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.648      0.463       0.55      0.394

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1325/7999     12.1G   0.02334  0.008173   0.01582       292       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.674      0.397      0.564      0.391

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1326/7999     12.1G   0.02319  0.007925    0.0183       285       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.654      0.413      0.562      0.398

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1327/7999     12.1G   0.02136  0.007953    0.0151       291       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130       0.43      0.699      0.575      0.408

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1328/7999     12.1G   0.02322   0.00748   0.01835       268       320: 100% 1/1 [00:01<00:00,  1.21s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.14it/s]
                 all        101        130      0.448       0.72      0.587      0.421

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1329/7999     12.1G   0.02252  0.008143   0.01813       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.462      0.737      0.593      0.415

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1330/7999     12.1G   0.02058  0.007477   0.01966       264       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.485       0.71      0.596      0.418

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1331/7999     12.1G   0.02278  0.007333   0.02038       259       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.768      0.393      0.619      0.432

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1332/7999     12.1G   0.02196  0.008753   0.01493       301       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.836      0.392      0.631      0.445

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1333/7999     12.1G    0.0236  0.007293   0.01697       258       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.807      0.391       0.63      0.455

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1334/7999     12.1G   0.02033  0.007439   0.01766       274       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.14it/s]
                 all        101        130      0.803      0.405       0.63      0.456

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1335/7999     12.1G   0.02246  0.007491   0.01561       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.763      0.476      0.643      0.461

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1336/7999     12.1G   0.02096  0.008432   0.01581       323       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.717      0.479      0.615      0.437

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1337/7999     12.1G   0.02336  0.007957   0.01837       287       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.647      0.548      0.593      0.424

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1338/7999     12.1G   0.02298  0.008463   0.01657       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.702       0.43      0.576      0.417

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1339/7999     12.1G   0.02177  0.008185   0.01744       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.624      0.423      0.585      0.411

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1340/7999     12.1G    0.0227  0.008248   0.01475       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.697      0.438      0.615      0.434

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1341/7999     12.1G   0.02342   0.00786   0.01636       285       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.696      0.463      0.644      0.444

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1342/7999     12.1G   0.02235  0.008215     0.018       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.647      0.456      0.647      0.451

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1343/7999     12.1G   0.02279  0.006968   0.01737       265       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.388      0.697      0.628      0.428

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1344/7999     12.1G   0.02304  0.008729   0.01514       304       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.386      0.694      0.606      0.422

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1345/7999     12.1G   0.02239  0.007374   0.01673       268       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.397      0.725      0.598      0.422

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1346/7999     12.1G   0.02083   0.00709   0.01528       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.387      0.685      0.576      0.409

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1347/7999     12.1G   0.02012  0.007653   0.01669       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.407      0.683      0.574      0.398

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1348/7999     12.1G    0.0211  0.007517   0.01504       280       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130        0.4      0.669      0.574      0.403

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1349/7999     12.1G   0.02153  0.008306   0.01706       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130        0.4      0.664      0.582      0.416

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1350/7999     12.1G   0.02312  0.008284   0.01592       299       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.382      0.685      0.597      0.435

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1351/7999     12.1G   0.02268  0.008619   0.01859       318       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.432      0.688      0.625      0.461

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1352/7999     12.1G   0.02258  0.007887   0.01647       277       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.426      0.689      0.621      0.459

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1353/7999     12.1G   0.02278  0.007619   0.01553       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130       0.44      0.691      0.624       0.45

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1354/7999     12.1G   0.02256  0.007522   0.01685       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.463      0.677      0.649      0.481

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1355/7999     12.1G   0.02214    0.0082   0.01634       289       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.464      0.689      0.637       0.47

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1356/7999     12.1G   0.02152  0.007918   0.02023       295       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.451      0.661      0.616      0.454

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1357/7999     12.1G   0.02206   0.00806   0.01498       288       320: 100% 1/1 [00:01<00:00,  1.19s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.448      0.631      0.572      0.423

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1358/7999     12.1G   0.02211  0.007662   0.01586       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.447      0.634      0.558      0.407

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1359/7999     12.1G   0.02141  0.007244   0.01549       282       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.449      0.627      0.556      0.415

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1360/7999     12.1G    0.0212  0.008473   0.01609       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.434      0.625      0.514      0.388

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1361/7999     12.1G   0.02279  0.007847   0.01774       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.449      0.628      0.506       0.38

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1362/7999     12.1G    0.0238  0.008621   0.01539       302       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.43      0.634      0.547      0.405

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1363/7999     12.1G   0.02169  0.007371   0.01792       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130       0.42      0.662      0.548      0.391

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1364/7999     12.1G   0.02223  0.007931   0.01675       281       320: 100% 1/1 [00:01<00:00,  1.15s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.66       0.42      0.566      0.403

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1365/7999     12.1G   0.02042  0.006981   0.01672       266       320: 100% 1/1 [00:01<00:00,  1.35s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.667      0.428       0.59      0.403

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1366/7999     12.1G   0.02267  0.007703    0.0176       274       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130       0.44      0.691      0.614      0.435

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1367/7999     12.1G   0.02286  0.007317   0.01677       261       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.455      0.726      0.634      0.431

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1368/7999     12.1G   0.02154  0.007849   0.01793       275       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.464      0.694      0.638      0.439

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1369/7999     12.1G   0.02136  0.008133   0.01218       304       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.471       0.72      0.643      0.426

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1370/7999     12.1G   0.02444  0.008258   0.01433       298       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.473      0.733      0.642      0.438

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1371/7999     12.1G   0.02411  0.008228   0.01575       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.608      0.554      0.617      0.406

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1372/7999     12.1G   0.02243  0.006846   0.01703       270       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.562      0.616      0.623      0.426

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1373/7999     12.1G   0.02336  0.008235   0.01699       291       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130       0.63      0.552      0.631      0.415

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1374/7999     12.1G   0.01863   0.00667   0.02045       250       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.617      0.569      0.607      0.403

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1375/7999     12.1G   0.02348  0.007896   0.01711       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.594      0.559        0.6      0.398

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1376/7999     12.1G   0.02457  0.007554   0.01789       274       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130      0.588      0.585      0.578      0.392

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1377/7999     12.1G   0.02152  0.008427   0.01644       289       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.559      0.599      0.554      0.372

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1378/7999     12.1G    0.0214  0.007556   0.01535       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.497      0.661      0.552      0.366

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1379/7999     12.1G   0.02166  0.008108   0.01474       286       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.504      0.467      0.551      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1380/7999     12.1G   0.02204  0.007248    0.0183       268       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130       0.52       0.47      0.535      0.354

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1381/7999     12.1G   0.02027   0.00807   0.01496       305       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.497      0.471      0.517      0.347

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1382/7999     12.1G   0.02173  0.007873   0.01601       271       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.368      0.627       0.48      0.329

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1383/7999     12.1G   0.02057  0.007349    0.0168       271       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.392      0.658      0.479      0.328

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1384/7999     12.1G   0.02035  0.007576   0.01548       271       320: 100% 1/1 [00:01<00:00,  1.18s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.407      0.601      0.474      0.326

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1385/7999     12.1G   0.02265  0.007669   0.01533       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.418      0.603       0.48      0.331

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1386/7999     12.1G   0.01982  0.007034   0.01334       286       320: 100% 1/1 [00:01<00:00,  1.20s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.14it/s]
                 all        101        130      0.418       0.63       0.49      0.342

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1387/7999     12.1G   0.02244  0.006755   0.01753       262       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.451       0.65      0.498      0.343

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1388/7999     12.1G   0.02105  0.007645   0.01452       292       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.46      0.651      0.508      0.352

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1389/7999     12.1G   0.02114  0.007273   0.01758       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.453      0.646      0.508      0.347

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1390/7999     12.1G   0.02147  0.008152   0.01544       302       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.23it/s]
                 all        101        130      0.458      0.647      0.508      0.347

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1391/7999     12.1G   0.02189  0.007095   0.01511       290       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.443      0.599      0.483      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1392/7999     12.1G   0.02172  0.008147   0.01436       315       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.22it/s]
                 all        101        130      0.438      0.571      0.471       0.32

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1393/7999     12.1G   0.02221  0.006945   0.01763       272       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.19it/s]
                 all        101        130      0.447       0.61      0.481      0.331

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1394/7999     12.1G    0.0211  0.008211   0.01611       284       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.404      0.541      0.466      0.317

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1395/7999     12.1G   0.02359  0.007828   0.01383       291       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.25it/s]
                 all        101        130       0.36      0.508      0.412      0.271

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1396/7999     12.1G   0.02215  0.008038   0.01506       293       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.319      0.494      0.409      0.278

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1397/7999     12.1G   0.02182  0.008513   0.01631       284       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.361      0.484      0.423      0.289

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1398/7999     12.1G   0.02304  0.007493   0.01665       276       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.26it/s]
                 all        101        130      0.366      0.593      0.449      0.311

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1399/7999     12.1G    0.0215   0.00794   0.01782       276       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.464      0.613      0.496      0.357

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1400/7999     12.1G   0.01949  0.007316   0.02024       267       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.454      0.644      0.541      0.394

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1401/7999     12.1G   0.02311  0.007964   0.01532       300       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.47      0.693      0.556      0.383

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1402/7999     12.1G   0.01998  0.006758   0.01606       267       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130       0.48      0.692      0.553      0.377

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1403/7999     12.1G   0.02247  0.007474   0.01656       282       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.17it/s]
                 all        101        130      0.481      0.708      0.547      0.357

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1404/7999     12.1G   0.02113  0.007524    0.0167       279       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.16it/s]
                 all        101        130       0.48      0.698       0.54      0.351

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1405/7999     12.1G   0.02186  0.007602   0.01589       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.15it/s]
                 all        101        130      0.439      0.678      0.521      0.324

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1406/7999     12.1G   0.02101  0.006723   0.01553       259       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.437      0.695      0.523      0.327

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1407/7999     12.1G   0.02277  0.007815   0.01776       262       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130       0.42      0.704      0.538      0.329

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1408/7999     12.1G   0.02104  0.006954   0.02079       242       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.423      0.688      0.512      0.315

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1409/7999     12.1G   0.02275  0.007277   0.01825       264       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.439      0.704      0.516      0.314

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1410/7999     12.1G   0.02196  0.007673   0.01488       297       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.437       0.69      0.548      0.323

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1411/7999     12.1G    0.0225  0.007689   0.01736       278       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.21it/s]
                 all        101        130      0.364      0.639      0.496      0.302

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1412/7999     12.1G   0.02276  0.007367   0.01898       285       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.371      0.644      0.486        0.3

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1413/7999     12.1G   0.02351   0.00748   0.01346       287       320: 100% 1/1 [00:01<00:00,  1.17s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.20it/s]
                 all        101        130      0.347      0.631      0.481      0.304

     Epoch   gpu_mem       box       obj       cls    labels  img_size
 1414/7999     12.1G   0.02208  0.008538    0.0157       294       320: 100% 1/1 [00:01<00:00,  1.16s/it]
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:00<00:00,  1.18it/s]
                 all        101        130      0.356      0.644      0.505      0.328
Stopping training early as no improvement observed in last 800 epochs. Best results observed at epoch 614, best model saved as best.pt.
To update EarlyStopping(patience=800) pass a new patience value, i.e. `python train.py --patience 300` or use `--patience 0` to disable EarlyStopping.

1415 epochs completed in 1.128 hours.
Optimizer stripped from runs/train/exp/weights/last.pt, 42.1MB
Optimizer stripped from runs/train/exp/weights/best.pt, 42.1MB

Validating runs/train/exp/weights/best.pt...
Fusing layers... 
Model summary: 290 layers, 20861016 parameters, 0 gradients, 47.9 GFLOPs
               Class     Images     Labels          P          R     mAP@.5 mAP@.5:.95: 100% 1/1 [00:01<00:00,  1.14s/it]
                 all        101        130      0.758      0.537      0.777      0.574
                fork        101         83      0.847        0.2       0.73       0.49
               knife        101         31      0.612      0.662      0.738      0.608
               spoon        101         16      0.814       0.75      0.863      0.623
Results saved to runs/train/exp
wandb: Waiting for W&B process to finish... (success).
wandb:                                                                                
wandb: 
wandb: Run history:
wandb:      metrics/mAP_0.5 ▁▅██▆▆▄▅▅▅▄▅▆▅▆▆▆█▆▆▆▇▇▆█▅▄▆▆▆▆▇▆▆▇▇▆▇▇▆
wandb: metrics/mAP_0.5:0.95 ▁▄▇█▅▆▄▅▆▅▄▅▆▆▆▆▆▇▆▆▆▇▇▆█▅▅▆▆▆▆▇▆▇▆▇▆▇▇▆
wandb:    metrics/precision ▁▅█▇▆▆▃▄▅▆▄▄▅▆▆▆▇▆▄▅▄▄▆▅▅▄▆▄▆▄▆▆▄▄▄▆▆▄▄▄
wandb:       metrics/recall ▃▂▂▄▃▃▃▅▆▂▃▄▆▃▃▂▁▄▅▄▆▆█▃█▅▂▇▃▄▃▃▆▇█▄▂▇▆▇
wandb:       train/box_loss █▄▄▃▃▂▂▂▂▁▂▂▂▂▂▂▂▁▁▁▂▁▁▂▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
wandb:       train/cls_loss █▆▅▅▄▄▃▃▃▂▃▃▃▃▂▂▂▃▃▂▂▂▂▂▃▃▂▂▂▂▂▂▁▃▂▁▂▁▁▂
wandb:       train/obj_loss █▇▅▄▃▂▂▂▂▂▂▂▂▂▂▂▂▂▁▁▂▁▁▂▂▁▂▁▂▁▁▂▁▁▁▁▁▁▁▁
wandb:         val/box_loss █▅▂▂▁▂▃▁▁▁▄▂▂▂▃▂▁▃▃▂▁▁▁▂▁▂▄▂▃▂▂▃▁▁▁▂▂▃▁▁
wandb:         val/cls_loss ▂▃▄▄█▆▅▄█▆▄▆▆▄▅▇▄▆▄▄▅▄▆▄▁▃▇▄▄▄▇▄▅▄▃▄▄▆▇▃
wandb:         val/obj_loss █▄▁▁▃▅▆▅▅▄▃▅▆█▂▆▅▄▅▅▅▄▂▄▂▆█▅▆▆▄▅▅▃▄▃▆▃▃▄
wandb:                x/lr0 █▅▃▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁
wandb:                x/lr1 ▁▄▆██████████████▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇
wandb:                x/lr2 ▁▄▆██████████████▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇▇
wandb: 
wandb: Run summary:
wandb:           best/epoch 614
wandb:         best/mAP_0.5 0.77725
wandb:    best/mAP_0.5:0.95 0.57337
wandb:       best/precision 0.7574
wandb:          best/recall 0.53719
wandb:      metrics/mAP_0.5 0.77717
wandb: metrics/mAP_0.5:0.95 0.5738
wandb:    metrics/precision 0.75767
wandb:       metrics/recall 0.53734
wandb:       train/box_loss 0.02208
wandb:       train/cls_loss 0.0157
wandb:       train/obj_loss 0.00854
wandb:         val/box_loss 0.04046
wandb:         val/cls_loss 0.05789
wandb:         val/obj_loss 0.00666
wandb:                x/lr0 0.00825
wandb:                x/lr1 0.00825
wandb:                x/lr2 0.00825
wandb: 
wandb: Synced splendid-puddle-70: https://wandb.ai/fernando-sinesio/YOLOv5/runs/c2lj6niz
wandb: Synced 5 W&B file(s), 45 media file(s), 1 artifact file(s) and 0 other file(s)
wandb: Find logs at: ./wandb/run-20220813_200753-c2lj6niz/logs
  ```
</details>

### Evidências do treinamento

Nessa seção você deve colocar qualquer evidência do treinamento, como por exemplo gráficos de perda, performance, matriz de confusão etc.

![Accuracy](https://raw.githubusercontent.com/Fernandosinesio/cutlery/main/assets/best%20epoch%20accuracy.png)
![Metrics graphs](https://raw.githubusercontent.com/Fernandosinesio/cutlery/main/assets/metrics%20graphs.png)
![Confusion Matrix](https://raw.githubusercontent.com/Fernandosinesio/cutlery/main/assets/confusion_matrix.png)
![Results](https://raw.githubusercontent.com/Fernandosinesio/cutlery/main/assets/results.png)
https://wandb.ai/fernando-sinesio/YOLOv5/reports/metrics-mAP_0-5-0-95-22-08-14-17-08-09---VmlldzoyNDczNTgy?accessToken=yzikz7ys5pufigtd68hr7rb521cs9qy3xa1bgbgu467sa65886hwmkujc482gjyl<br>
https://wandb.ai/fernando-sinesio/YOLOv5/reports/metrics-recall-22-08-14-17-08-89---VmlldzoyNDczNjI2?accessToken=id4993430jym83dx9y5rhnakdmgyfcpkd01a4e6k36x1mol2jf7s60k8fo6u00c5<br>
https://wandb.ai/fernando-sinesio/YOLOv5/reports/metrics-mAP_0-5-22-08-14-17-08-98---VmlldzoyNDczNjI4?accessToken=rq3b2sjogvwg421j9u36jci7caluqxj17l4smaj9i9m5aheq1x7uu1y8t1kyzeo1<br>
https://wandb.ai/fernando-sinesio/YOLOv5/reports/metrics-precision-22-08-14-17-08-03---VmlldzoyNDczNjI5?accessToken=gdtpu0e0u0sad1y3tacykddgwe3nhmej390n0wgd27x2r8wtfiphruyfkvyt1h8l<br>
https://wandb.ai/fernando-sinesio/YOLOv5/reports/train-cls_loss-22-08-14-17-08-33---VmlldzoyNDczNjMw?accessToken=rr0d5ku6rayek9o13qs1tdg6chwg13ezg2lv8352sm3w1c185njqt3tt28g2f4q9<br>
https://wandb.ai/fernando-sinesio/YOLOv5/reports/train-obj_loss-22-08-14-17-08-47---VmlldzoyNDczNjMx?accessToken=v0rlsljr4ggt0huudm0orj6w9i422jwns0sewcos3rya1qs85flbhgp21ec8oo2q<br>
https://wandb.ai/fernando-sinesio/YOLOv5/reports/train-box_loss-22-08-14-17-08-79---VmlldzoyNDczNjMy?accessToken=7bki8h8c1598yqj9qk0m0opbpkvh1ora7lx7nosc39wtan7wivjg8tg5tgtao5gk<br>




## Roboflow

Nessa seção deve colocar o link para acessar o dataset no Roboflow

[Roboflow cutlery_class Image Dataset](https://app.roboflow.com/fernandosinesio/cutlery_class/11)

## HuggingFace

Nessa seção você deve publicar o link para o HuggingFace

Dataset: FernandoSinesio/cutlery<br>
Aplicação: https://huggingface.co/spaces/FernandoSinesio/cutlery