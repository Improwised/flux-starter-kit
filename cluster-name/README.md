## flux-system

To install the flux on  cluster, follow the steps.

### Step: 1
  Clone this Improwised/flux-starter-kit repo.
  
    git clone <clone link>
    
### Step: 2
  Navigate to directory named flux-system in newly cloned repo.
  
    cd flux-starter-kit/cluster-name/flux-system/
    
### Step: 3
  Now, apply the CRDs and tools of flux to the cluster by following command.
  
    kubectl apply -k ./flux-crds
### Flux installation completed.
and flux starts syncing the `cluster-name` Directory.
